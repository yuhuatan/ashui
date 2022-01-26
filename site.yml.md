 #    准备环境、安装ceph软件 
     所有ceph节点加载配置、检查部署环境、配置网络等、安装ceph软件
 ##   01 检查python环境，没有就安装 [import_tasks  raw_install_python.yml ] 
     ansible管理远程主机依赖于远程主机有python环境, raw_install_python.yml会检查是否python环境是否安装好，没有就安装

 ##   02 获取facts ?

 ##   03 加载部署ceph集群过程中需要的用到的变量 [import_role ceph-defaults]
     ceph集群部署过程中用到的很多变量都定义在ceph-defaults role中，比如ceph集群名称,各个ceph服务组的组名等等
 ##   04 设置facts [import_role ceph-facts] 
     设置一些供后面的role使用的参数，这些参数不能预先定义在ceph-defaults里面，ceph-defaults中都是预先确定的参数，而有些参数需要根据系统配置或者集群状态的信息来确定。比如需要根据系统版本确定容器管理程序是podman还是docker，要根据主机名确定各个monitor节点的monitor_name，要根据部署方式确定ceph服务启动方式是podman run还是ceph，比如后面的ceph-config role需要根据这里设置的一些facts渲染模版文件。确定集群的fsid、crush规则,设置monitor ip、radosgw ip
     设置ceph管理命令（ceph -n client.admin -k /etc/ceph/ceph.client.admin.keyring）
     设置rgw端口、rgw_zone


 ##   05 设置ceph各个服务参数 [import_role ceph-handler]
 ###     06-01-00 include # include check_running_cluster.yml ,检查ceph集群中各种服务的socket文件是否存在，以及是否被进程在使用，以及各种ceph相关进程的pid
      06-01-01_skipping include_tasks # include check_running_containers.yml ,以容器方式部署时导入检查容器的tasks
      06-01-02_ok include_tasks # include check_socket_non_container.yml ,非容器方式部署时导入检查服务socket的tasks,检查ceph-mon、ceph-osd、ceph-rgw、mds、等daemon的socket文件是否存在，是否被进程在使用，ceph-crash pid等
      06-01-02-01_ok task # find ceph mon socket ,查找ceph-mon节点的ceph-mon服务的socket文件
      06-01-02-02_skipping task # check if the ceph mon socket is in-use ,ceph-mon服务的socket文件存在（这里不存在）时检查ceph-mon服务的socket文件是否在使用
      06-01-02-03_skipping task # remove ceph mon socket if exists and not used by a process ,ceph-mon服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-mon服务的socket文件
      06-01-02-04_ok task # find ceph osd socket ,查找ceph-osd服务的socket文件
      06-01-02-05_skipping task # check if the ceph osd socket is in-use ,ceph-osd服务的socket文件存在（这里不存在）时检查ceph-osd服务的socket文件是否在使用
      06-01-02-06_skipping task # remove ceph osd socket if exists and not used by a process ,ceph-osd服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-osd服务的socket文件
      06-01-02-07_skipping task # find ceph mds socket ,查找ceph-mds服务的socket文件
      06-01-02-08_skipping task # check if the ceph mds socket is in-use ,mds服务相关
      06-01-02-09_skipping task # remove ceph mds socket if exists and not used by a process ,mds服务相关
      06-01-02-01_ok task # find ceph rgw socket ,查找ceph-rgw服务的socket文件
      06-01-02-11_skipping task # check if the ceph rgw socket is in-use ,ceph-rgw服务的socket文件存在（这里不存在）时检查ceph-rgw服务的socket文件是否在使用
      06-01-02-12_skipping task # remove ceph rgw socket if exists and not used by a process ,ceph-rgw服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-rgw服务的socket文件
      06-01-02-13_ok task # find ceph mgr socket ,查找ceph-mgr服务的socket文件
      06-01-02-13_skipping task # check if the ceph mgr socket is in-use ,ceph-mgr服务的socket文件存在（这里不存在）时检查ceph-mgr服务的socket文件是否在使用
      06-01-02-14_skipping task # remove ceph mgr socket if exists and not used by a process ,ceph-mgr服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-mgr服务的socket文件
      06-01-02-15_skipping task # find ceph rbd mirror socket ,查找ceph-rbd服务的socket文件
      06-01-02-16_skipping task # check if the ceph rbd mirror socket is in-use ,rbd服务相关
      06-01-02-17_skipping task # remove ceph rbd mirror socket if exists and not used by a process ,rbd服务相关
      06-01-02-18_skipping task # check for a nfs ganesha pid ,nfs服务相关
      06-01-02-19_skipping task # check for a tcmu-runner ,iscsi服务相关
      06-01-02-20_skipping task # check for a rbd-target-api ,iscsi服务相关
      06-01-02-21_skipping task # check for a rbd-target-gw ,iscsi服务相关
      06-01-02-22_ok task # check for a ceph-crash process ，获取ceph-crash的pid
 ###  06-02-00_ok task # set_fact handler_mon_status ,如果ceph-mon的socket文件存在且被进程在使用则将handler_mon_status设置为true,这里为false
 ###  06-03-00_ok task # set_fact handler_osd_status ,如果ceph-osd的socket文件存在且被进程在使用则将handler_osd_status设置为true,这里为false
 ###  06-04-00_skipping task # set_fact handler_mds_status ,mds相关
 ###  06-05-00_ok task # set_fact handler_rgw_status ,如果ceph-rgw的socket文件存在且被进程在使用则将handler_rgw_status设置为true,这里为false
 ###  06-06-00_skipping task # set_fact handler_nfs_status ,nfs相关
 ###  06-07-00_skipping task # set_fact handler_rbd_status ,rbd相关
 ###  06-08-00_ok task # set_fact handler_mgr_status ,如果ceph-mgr的socket文件存在且被进程在使用则将handler_mgr_status设置为true,这里为false
 ###  06-09-00_ok task # set_fact handler_crash_status ,如果ceph-crash的socket文件存在且被进程在使用则将handler_crash_status设置为true,这里为false
        06-10-00_skipping block # rgw multi-instances related tasks ,rgw多实例相关tasks
      06-10-01 import_role # import_role ceph-config ,导入ceph配置role
      06-10-01-01_skipping include_tasks # include create_ceph_initial_dirs.yml ,容器化部署ceph时导入目录初始化tasks
      06-10-01-02_skipping include_tasks # include_tasks rgw_systemd_environment_file.yml ,?
      06-10-01-03_skipping block # include_tasks config file operations related to OSDs ,?
      06-10-01-03-01_skipping task # reset num_osds ,设置osd数量num_osds为0
      06-10-01-03-02_skipping task # count number of osds for lvm scenario ,统计osd使用lvm场景的osd数量
      06-10-01-03-03_skipping block # 
      06-10-01-03-03-01_skipping task # look up for ceph-volume rejected devices, 
      06-10-01-03-03-02_skipping task # set_fact rejected_devices, 
      06-10-01-03-03-03_skipping task # set_fact _devices, 
      06-10-01-03-03-04_skipping task # run 'ceph-volume lvm batch --report' to see how many osds are to be created, 
      06-10-01-03-03-05_skipping task # set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report), 
      06-10-01-03-03-06_skipping task # set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report), 
      06-10-01-03-04_skipping task # run 'ceph-volume lvm list' to see how many osds have already been created,
      06-10-01-03-05_skipping task # set_fact num_osds (add existing osds),
      06-10-01-04_skipping block # create ceph conf directory,?
      06-10-01-05_skipping block # "generate {{ cluster }}.conf configuration file",?
      06-10-02 import_role # import_role ceph-rgw/pre_requisite.yml ,非容器部署时导入 # ***
      06-10-02-01_skipping task # create rgw keyrings ,
      06-10-03 import_role # import_role ceph-rgw/multisite.yml ,
      06-10-03-01_skipping include_tasks # include_tasks multisite ,
      06-10-04 task # set_fact multisite_called_from_handler_role ,

 ##   06 确认配置 [import_role ceph-validate] 
     确认各项配置（系统、网络、磁盘、软件仓库等等）

      07-01-00 include_tasks # include check_system.yml ,检查ansible版本，系统版本，服务管理软件是否达到要求的tasks，不满足要求会报错退出
      07-01-01_skipping task # fail on unsupported ansible version (1.X) ,ansible主版本小于2时报错,退出playbook执行。
      07-01-02_skipping task # fail on unsupported ansible version ,ansible次版本小于9时报错,退出playbook执行。
      07-01-03_skipping task # fail on unsupported system, 待执行的主机系统不是linux时报错,退出playbook执行。
      07-01-04_skipping task # fail on unsupported architecture, 待执行的主机系统不是x86_64等架构时报错,退出playbook执行。
      07-01-05_skipping task # fail on unsupported distribution, 待执行的主机系统不是RedHat、Debian等发行版时报错,退出playbook执行。
      07-01-06_skipping task # fail on unsupported CentOS release, 待执行的主机系统是CentOS 7时报错,退出playbook执行。
      07-01-07_skipping block # red hat based systems tasks, 待执行的主机系统为RedHat且使用红帽的软件仓库安装ceph时相关tasks,这里跳过
      07-01-08_skipping task # fail on unsupported distribution for ubuntu cloud archive, 待执行的主机系统为Ubuntu且使用ubuntu的软件仓库安装ceph时报错,退出playbook执行
      07-01-09_skipping task # "fail on unsupported SUSE/openSUSE distribution (only 15.x supported)", 待执行的主机系统为SUSE且主版本为15时报错,退出playbook执行
      07-01-01_skipping task # fail if systemd is not present, 待执行主机系统的服务管理程序必须是systemd，否则报错,退出playbook执行
 ###     07-02-00 include_tasks # validate repository variables in non-containerized scenario ,确认非容器部署场景下的仓库配置是否正确
      07-02-01_skipping task # validate ceph_origin ,ceph源不是repository、distro、local时报错退出playbook，这里是repository
      07-02-02_skipping task # validate ceph_repository ,ceph是repository但是ceph_repository不在community、custom里面时报错退出playbook，这里是ceph_repository是custom
      07-02-03_skipping task # validate ceph_repository_community ,ceph是repository且ceph_repository是community，但是ceph版本号不是octopus时报错退出playbook，
 ###  07-03-00_skipping task # validate osd_objectstore ,确认osd存储引擎是bluestor或者filestore，否则报错退出playbook
 ###  07-04-00_skipping task # validate monitor network configuration ,确认ceph-monitor的网络配置无误，否则报错退出playbook
 ###  07-05-00_skipping task # validate radosgw network configuration ,确认radosgw的网络配置无误，否则报错退出playbook
 ###  07-06-00 block # validate osd nodes ,确认osd nodes相关tasks
      07-06-01_skipping task # validate lvm osd scenario ,没有开启osd自动发现且没有定义devices同时lvm_volumes也没有定义时报错,退出playbook
      07-06-02_skipping task # validate filestore lvm osd scenario ,使用filestore存储引擎时在lvm_volumes定义中必须定义data和journal否则报错,退出playbook
      07-06-03_skipping task # validate bluestore lvm osd scenario ,使用bluestore存储引擎时在lvm_volumes定义中必须定义data否则报错,退出playbook
 ###  07-07-00_skipping block # debian based systems tasks ,Debian系统相关的tasks
 ###  07-08-00_skipping block # SUSE/openSUSE Leap based system tasks ,SUSE/openSUSE系统相关的tasks
 ###  07-09-00_skipping task # validate ntp daemon type ,ntp服务的守护进程必须是['chronyd', 'ntpd', 'timesyncd']其中之一，否则报错，退出playbook
 ###  07-10-00_skipping task # validate ntp daemon type ,如果待执行主机的系统是RedHat原子系统，且ntp的守护进程为ntpd，则报错退出palybook
 ###  07-11-00_skipping task # make sure journal_size configured ,osd的存储引擎为filestore时如果journal_size小于5G则打印debug信息。
 ###  07-12-00 include_tasks # include check_devices.yml, 没有开启osd磁盘自动发现时，检查配置的osd盘
 ###  07-12-01_ok task # set_fact root_device, 把根盘对应的磁盘赋值给变量root_device
 ###  07-12-02_ok block # lvm_volumes variable's tasks related, lvm_volumes变量的相关tasks
 ###  07-12-02-01_ok task # resolve devices in lvm_volumes, 解析出lvm_volumes的data盘
 ###  07-12-02-02_ok task # set_fact lvm_volumes_data_devices, 设置lvm_volumes data盘
 ###  07-12-03_skipping task # fail if root_device is passed in lvm_volumes or devices, 当根盘在lvm_volumes或者devices中时报错退出playbook
 ###  07-12-04 block # check devices are block devices, 检查devices都是块设备
 ###  07-12-04-01_ok block # get devices information, 获取设备信息
 ###  07-12-04-02_skipping block # fail if one of the devices is not a device, 如果有一个设备不是磁盘则报错退出playbook
 ###  07-12-04-03_skipping block # fail when gpt header found on osd devices, 如果磁盘头发现gpt分区信息则报错退出playbook
 ###  07-12-05_ok block # check logical volume in lvm_volumes, 检查lvm_volumes中的lv
 ###  07-12-05-01_skipping task # check data logical volume, 获取vg下的lv的状态，这里vg不存在。
 ###  07-12-05-02_skipping task # fail if one of the data logical volume is not a device or doesn't exist, 当逻辑盘不是块设备或者不存在时报错退出playbook
 ###  07-12-05-03_skipping task # check bluestore db logical volume, 检查bluestore的db盘
 ###  07-12-05-04_skipping task # fail if one of the bluestore db logical volume is not a device or doesn't exist, 当bluestore的db盘不是块设备或者不存在时报错退出playbook
 ###  07-12-05-05_skipping task # check bluestore wal logical volume, 检查bluestore的wal盘
 ###  07-12-05-06_skipping task # fail if one of the bluestore wal logical volume is not a device or doesn't exist, 当bluestore的wal盘不是块设备或者不存在时报错退出playbook
 ###  07-12-05-07_skipping task # check filestore journal logical volume, 检查filestore的journal盘
 ###  07-12-05-07_skipping task # fail if one of the filestore journal logical volume is not a device or doesn't exist, 当filestore的journal盘不是块设备或者不存在时报错退出playbook
 ###  07-13-00 include_tasks # include check_eth_mon.yml, 检查ceph-mon的网卡状态及ip地址配置情况，有问题就报错退出playbook
 ###  07-13-01_skipping task # "fail if {{ monitor_interface }} does not exist on {{ inventory_hostname }}", monitor_interface不在待执行主机的facts里面时报错，退出playbook
 ###  07-13-02_skipping task # "fail if {{ monitor_interface }} is not active on {{ inventory_hostname }}", 待执行主机的monitor_interface不是active状态时报错，退出playbook
 ###  07-13-03_skipping task # "fail if {{ monitor_interface }} does not have any ip v4 address on {{ inventory_hostname }}", 待执行主机使用ipv4时monitor_interface没有ipv4地址就报错，退出playbook
 ###  07-13-04_skipping task # "fail if {{ monitor_interface }} does not have any ip v6 address on {{ inventory_hostname }}", 待执行主机使用ipv6时monitor_interface没有ipv6地址就报错，退出playbook
 ###  07-14-00 include_tasks # include check_ipaddr_mon.yml, 检查ceph-mon的网卡状态及ip地址配置情况，有问题就报错退出playbook
 ###  07-15-00 include_tasks # include check_eth_rgw.yml, 检查rgw的网卡状态及ip地址配置情况，有问题就报错退出playbook
 ###  07-16-00 include_tasks # include check_rgw_pools.yml, 检查ec（纠删码）rgw pool的配置文件及k和m值是否有配置，有问题就报错退出playbook
 ###  07-17-00 include_tasks # include check_rgw_multisite.yml, 检查rgw mulitsite的配置(masterzone,secondyzone,realm,user,ak/sk)，有问题就报错退出playbook
 ###  07-18-00 include_tasks # include check_iscsi.yml, 检查iscsi的配置，有问题就报错退出playbook
 ###  07-19-00 debug # warn about radosgw_civetweb_num_threads option deprecation, 检查civetweb的线程数配置。
 ###  07-20-00 include_tasks # include check_nfs.yml, 检查nfs相关配置
 ###  07-21-00 include_tasks # include check_rbdmirror.yml, 检查rbdmirror相关配置
 ###  07-22-00 block # check grafana-server config, 启用dashboard时检查grafana-server的配置（组是否存在，组里面是否有主机，密码是否配置）
 ###  07-23-00 fail # validate container registry credentials, ceph-docker 仓库启用认证时，检查认证信息是否配置正确，否则报错退出
 ###  07-24-00 fail # validate container service and container package, 检查容器包名和服务名配置，
 ###  07-25-00 fail # validate openstack_keys key format, 检查openstack keys相关
 ###  07-26-00 fail # validate clients keys key format, 检查client keys格式
 ###  07-27-00 fail # validate openstack_keys caps, 检查openstack keys权限
 ###  07-28-00 fail # validate clients keys key caps, 检查client keys权限
 ###  07-29-00 fail # check virtual_ips is defined, rgwloadbalancer检查虚拟ip的配置
 ###  07-30-00 fail # validate virtual_ips length, rgwloadbalancer检查虚拟ip的个数

 ##   07 配置防火墙、ntp、logrotate [import_role ceph-infra] 
  08-01-00 task # update cache for Debian based OSs ,Debian系统更新apt缓存
  08-02-00 include_tasks # include_tasks configure_firewall.yml ,配置防火墙
  08-03-00 include_tasks # include_tasks setup_ntp.yml ,配置ntp
  08-04-00 task # ensure logrotate is installed ,确保logrotate已安装
  08-05-00 task # add logrotate configuration ,添加logrotate配置

 ##   08 配置ceph仓库,安装ceph [import_role ceph-common]
   09-01-00 include_tasks # include configure_repository.yml ,配置ceph仓库
   09-02-00 include_tasks # include installs/install_redhat_packages.yml ,redhat系统安装依赖及ceph
   09-03-00 include_tasks # include installs/install_suse_packages.yml ,suse系统安装依赖及ceph
   09-04-00 include_tasks # include installs/install_on_debian.yml ,debian系统安装依赖及ceph
   09-05-00 include_tasks # include_tasks installs/install_on_clear.yml ,ClearLinux系统安装依赖及ceph
   09-06-00 task # get ceph version ,获取ceph版本
   09-07-00 task # set_fact ceph_version ,把获取到的ceph版本赋值给ceph_version
   09-08-00 include_tasks # include release-rhcs.yml, ceph仓库为rhcs/dev同事从发行版安装时设置ceph版本代号
   09-08-00 task # set_fact ceph_release - override ceph_release with ceph_stable_release, ceph仓库不是custom/rhcs/dev时设置ceph版本代号
   09-09-00 include_tasks # include create_rbd_client_dir.yml, 创建rbd client相关目录
   09-10-00 include_tasks # include configure_cluster_name.yml, 配置ceph集群名称
   09-11-00 include_tasks # include configure_memory_allocator.yml, 配置ceph集群各服务内存使用
   09-12-00 include_tasks # include selinux.yml, 配置selinux

 #   部署monitor
 ##  加载默认配置 [import_role ceph-defaults]
 ##  设置facts [import_role ceph-facts]
 ### 加载facts.yml
 ##  检查ceph各项服务状态[import_role ceph-handler]
 ##  [import_role ceph-config]

 #   部署mgr

 #   部署osd