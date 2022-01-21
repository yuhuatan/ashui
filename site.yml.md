 #  000 pre_tasks # 
 #  001 import_tasks # 检查是否安装了python，没有就安装。
 #  001-001_ok task # 获取几个python文件的状态，返回值赋值给注册变量 systempython
 ## 001-002_skipping task # 获取/bin/dnf-3文件的状态，返回值赋值给注册变量stat_dnf3，
 ## 001-003_skipping task # 获取/bin/yum文件的状态，返回值赋值给注册变量stat_yum，
 ## 001-004_skipping task # 获取/usr/bin/apt-get文件的状态，返回值赋值给注册变量stat_apt
 ## 001-005_skipping task # 获取/usr/bin/zypper文件的状态，返回值赋值给注册变量stat_zypper
 ## 001-006_skipping task # 在RedHat系列系统上安装python3
 ## 001-007_skipping task # 在debian系列系统上安装python
 ## 001-008_skipping task # 在SUSE/OpenSUSE系列系统上安装python
 #  001-009_skipping task # 在已安装python2的OpenSUSE系列系统上安装python-xml

 #  002_skipping task # 获取facts ?

 #  003_ok task # gather and delegate facts ?

 #  004 import_role # import ceph-defaults 导入ceph默认配置

 #  005 import_role # import ceph-facts ,设置一些facts,比如IP地址、rgw端口、rgw_zone、ceph管理命令等等
 #  005-001 include tasks # include facts.yml 
 #  005-001-001_ok task # 检查是否是原子主机系统，原子系统不是传统通用的操作系统，原子系统主要设计来运行容器。 
 #  005-001-002_ok task # is_atomic: false ,获取原子主机的检查状态赋值给注册变量is_atomic
 #  005-001-003 import_tasks # container_binary.yml 设置容器管理命令
 #  005-001-003-001_ok task # check if podman binary is present 检查podman是否存在
 #  005-001-003-002_ok task # set_fact container_binary 根据条件设置容器管理程序,这里为podman
 #  005-001-004_ok task # set_fact ceph_cmd 根据条件设置ceph启动命令，如果是容器方式部署就用podman启动，否则为ceph，这里是ceph
 #  005-001-005_skipping task # set_fact discovered_interpreter_python 根据条件设置discovered_interpreter_python,这里条件为false
 #  005-001-006_ok task # set_fact discovered_interpreter_python 根据条件设置discovered_interpreter_python: /usr/libexec/platform-python
 #  005-001-007_ok task # set_fact ceph_release ceph_stable_release 设置ceph版本为octopus
 #  005-001-008_ok task # set_fact monitor_name 设置各个monitor节点的monitor_name为主机名
 #  005-001-009 tasks # find a running monitor 找到一个running的monitor
 ## 005-001-009-001_skipping task # set_fact container_exec_cmd 以容器方式部署ceph时设置容器执行命令
 ## 005-001-009-002_skipping task # find a running mon container 以容器方式部署ceph时找到一个running的ceph-monitor容器
 ## 005-001-009-003_ok task # check for a ceph mon socket 在每一台monitor节点上检查socket文件是否存在,返回值赋值给mon_socket_stat
 ## 005-001-009-004_ok task # check if the ceph mon socket is in-use 检查每一台ceph-monitor上的ceph monitor socket 是否在使用,返回值赋值给mon_socket
 ## 005-001-009-005_skipping task # set_fact running_mon - non_container 非容器部署下如果ceph-monitor socket文件存在且正在使用，则将ceph-monitor主机名赋值给running_mon
 ## 005-001-009-006_skipping task # set_fact running_mon - container 容器部署下如果ceph-monitor 容器存在且正在使用，则将ceph-monitor主机名赋值给running_mon
 ## 005-001-009-007_skipping task # set_fact _container_exec_cmd 容器部署下设置容器执行命令
 ## 005-001-009-008_ok task # get current fsid if cluster is already running 非升级时获取当前集群的fsid
 #  005-001-010_skipping task # set_fact current_fsid rc 1 升级或者mons组中没有主机时设置当前的current_fsid为1
 #  005-001-011_skipping task # get current fsid 升级且mons组中没有主机数不为空时获取当前的current fsid赋值给rolling_update_fsid
 #  005-001-012_skipping task # set_fact fsid 升级且mons组中没有主机数不为空时设置fsid为rolling_update_fsid的stdout字段
 #  005-001-013_skipping task # set_fact fsid from current_fsid 上面的task005-001-009-008_ok 成功获取到fsid时把current_fsid.stdout赋值给fsid
 #  005-001-015 block # fsid related tasks 非升级且获取不到当前fsid同时generate_fsid变量为true时，fsid的相关操作,这里条件为true
 ## 005-001-015-001_changed task # generate cluster fsid 生成集群fsid赋值给cluster_uuid
 ## 005-001-015-002_ok task # set_fact fsid 设置fsid为cluster_uuid的stdout
 #  005-001-016 import_tasks # import_tasks devices.yml 执行主机在osds组中时导入devices的tasks,得到磁盘序列
 #  005-001-016-001_skipping task # resolve device link(s), devices有定义同时osd_auto_discovery为false时找出符号链接后面的真正磁盘文件
 #  005-001-016-002_skipping task # set_fact build devices from resolved symlinks, devices有定义同时osd_auto_discovery为false时根据上个task的返回设置磁盘盘符。
 #  005-001-016-003_skipping task # set_fact build devices from resolved symlinks, devices有定义同时osd_auto_discovery为false时根据上个task的返回设置磁盘序列。
 #  005-001-016-004_skipping task # resolve dedicated_device link(s), dedicated_devices有定义同时osd_auto_discovery为false时找出符号链接后面的真正磁盘文件
 #  005-001-016-005_skipping task # set_fact build dedicated_devices from resolved symlinks, dedicated_devices有定义同时osd_auto_discovery为false时根据上个task的返回拿到磁盘文件
 #  005-001-016-006_skipping task # set_fact build final dedicated_devices list, dedicated_devices有定义同时osd_auto_discovery为false时根据上个task的返回得到磁盘序列
 #  005-001-016-007_skipping task # resolve bluestore_wal_device link(s), bluestore_wal_devices有定义同时osd_auto_discovery为false时找到bluestore_wal_device符号链接指向的磁盘文件
 #  005-001-016-008_skipping task # set_fact build bluestore_wal_devices from resolved symlinks, bluestore_wal_devices有定义同时osd_auto_discovery为false时根据上个task的返回得到磁盘文件
 #  005-001-016-009_skipping task # set_fact build final bluestore_wal_devices list, bluestore_wal_devices有定义同时osd_auto_discovery为false时根据上个task的返回得到磁盘文件序列
 #  005-001-016-010_skipping task # set_fact devices generate device list when osd_auto_discovery, 开启osd磁盘自动发现时设置磁盘序列
 #  005-001-017_skipping block # backward compatibility tasks related, 向后兼容相关任务
 ## 005-001-017-001_skipping task # get ceph current status, 获取ceph集群服务各服务状态
 ## 005-001-017-002_skipping task # set_fact ceph_current_status, 上个task成功获取到集群服务状态时将服务状态信息赋值给ceph_current_status变量
 ## 005-001-017-003_skipping task # set_fact rgw_hostname, 上个task的变量ceph_current_status的rgw服务存在时提取rgw主机
 #  005-001-018_ok task# check if the ceph conf exists, 检查ceph.conf文件是否存在,返回值赋给注册变量ceph_conf
 #  005-001-019_ok task# set default osd_pool_default_crush_rule fact, 设置osd pool的默认crush规则，这个变量在role ceph-defaults/vars/main.yml中有定义
 #  005-001-020_skipping block# get default crush rule value from ceph configuration, ceph.conf配置文件存在时从中获取默认crush规则
 ## 005-001-020-001_skipping task# read osd pool default crush rule, ceph.conf配置文件存在时从中获取默认crush规则
 ## 005-001-020-002_skipping task# set osd_pool_default_crush_rule fact, 上个task成功获取到crush规则时设置crush规则
 #  005-001-021_skipping block# get default crush rule value from running monitor ceph configuration, ceph.conf配置文件不存在且running_mon有定义时从running的ceph-monitor获取crush规则
 #  005-001-022_ok import_tasks# import_tasks set_monitor_address.yml, 导入设置ceph-monitor ip地址的tasks
 ## 005-001-022-001_skipping task# set_fact _monitor_addresses to monitor_address_block ipv4 ?
 ## 005-001-022-002_skipping task# set_fact _monitor_addresses to monitor_address_block ipv6 ?
 ## 005-001-022-003_skipping task# set_fact _monitor_addresses to monitor_address ?
 ## 005-001-022-004_ok task# set_fact _monitor_addresses to monitor_interface - ipv4 ?
 ## 005-001-022-005_skipping task# set_fact _monitor_addresses to monitor_interface - ipv6 ?
 ## 005-001-022-006_ok task# set_fact _current_monitor_address ?
 #  005-001-023_ok import_tasks# import_tasks set_radosgw_address.yml, 导入设置radosgw ip地址的tasks
 ## 005-001-023-001_ok task# set_fact _radosgw_address to radosgw_address_block ipv4, ?
 ## 005-001-023-002_skipping task# set_fact _radosgw_address to radosgw_address_block ipv6, ?
 ## 005-001-023-003_skipping task# set_fact _radosgw_address to radosgw_address, ?
 #  005-001-023-004_skipping block# tasks for radosgw interface, ?
 ## 005-001-023-004-001_skipping task# set_fact _interface, ?
 ## 005-001-023-004-002_skipping task# set_fact _radosgw_address to radosgw_interface - ipv4, ?
 ## 005-001-023-004-003_skipping task# set_fact _radosgw_address to radosgw_interface - ipv6, ?
 #  005-001-023-005_skipping task# set_fact rgw_instances without rgw multisite|rgw_yh_es_sync, ?
 #  005-001-023-006_ok task# set_fact is_rgw_instances_defined, ?
 #  005-001-023-007_skipping task# set_fact rgw_instances with rgw multisite, ?
 #  005-001-023-008_ok task# set_fact rgw_yh_client_instances with rgw_yh_es_sync, 设置客户端rgw的port、zone、user、key、realm等信息
 #  005-001-023-009_ok task# set_fact rgw_yh_master_instances, 设置master rgw的port、zone、user、key、realm等信息
 #  005-001-023-010_ok task# set_fact rgw_yh_esync_instances, 设置esync rgw的port、zone、user、key、realm等信息
 #  005-001-023-011_ok task# set_fact rgw_instances with rgw_yh_es_sync, 设置es同步信息
 #  005-001-023-012_ok task# set_fact rgw_instances_host, 
 #  005-001-023-013_ok task# set_fact rgw_instances_all, 
 #  005-001-024_skipping task# set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli, iscsi相关
 #  005-001-025_ok task# set_fact ceph_run_cmd, 设置ceph启动命令，这里ceph_run_cmd为ceph
 #  005-001-026_ok task# set_fact ceph_admin_command, 设置ceph管理命令，这里ceph_admin_command为ceph -n client.admin -k /etc/ceph/ceph.client.admin.keyring

 #  006 import_role # import ceph-handler ,设置ceph各个服务参数
 #  006-001 include # include check_running_cluster.yml ,检查ceph集群中各种服务的socket文件是否存在，以及是否被进程在使用，以及各种ceph相关进程的pid
 #  006-001-001_skipping include_tasks # include check_running_containers.yml ,以容器方式部署时导入检查容器的tasks
 #  006-001-002_ok include_tasks # include check_socket_non_container.yml ,非容器方式部署时导入检查服务socket的tasks,检查ceph-mon、ceph-osd、ceph-rgw、mds、等daemon的socket文件是否存在，是否被进程在使用，ceph-crash pid等
 #  006-001-002-001_ok task # find ceph mon socket ,查找ceph-mon节点的ceph-mon服务的socket文件
 #  006-001-002-002_skipping task # check if the ceph mon socket is in-use ,ceph-mon服务的socket文件存在（这里不存在）时检查ceph-mon服务的socket文件是否在使用
 #  006-001-002-003_skipping task # remove ceph mon socket if exists and not used by a process ,ceph-mon服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-mon服务的socket文件
 #  006-001-002-004_ok task # find ceph osd socket ,查找ceph-osd服务的socket文件
 #  006-001-002-005_skipping task # check if the ceph osd socket is in-use ,ceph-osd服务的socket文件存在（这里不存在）时检查ceph-osd服务的socket文件是否在使用
 #  006-001-002-006_skipping task # remove ceph osd socket if exists and not used by a process ,ceph-osd服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-osd服务的socket文件
 #  006-001-002-007_skipping task # find ceph mds socket ,查找ceph-mds服务的socket文件
 #  006-001-002-008_skipping task # check if the ceph mds socket is in-use ,mds服务相关
 #  006-001-002-009_skipping task # remove ceph mds socket if exists and not used by a process ,mds服务相关
 #  006-001-002-010_ok task # find ceph rgw socket ,查找ceph-rgw服务的socket文件
 #  006-001-002-011_skipping task # check if the ceph rgw socket is in-use ,ceph-rgw服务的socket文件存在（这里不存在）时检查ceph-rgw服务的socket文件是否在使用
 #  006-001-002-012_skipping task # remove ceph rgw socket if exists and not used by a process ,ceph-rgw服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-rgw服务的socket文件
 #  006-001-002-013_ok task # find ceph mgr socket ,查找ceph-mgr服务的socket文件
 #  006-001-002-013_skipping task # check if the ceph mgr socket is in-use ,ceph-mgr服务的socket文件存在（这里不存在）时检查ceph-mgr服务的socket文件是否在使用
 #  006-001-002-014_skipping task # remove ceph mgr socket if exists and not used by a process ,ceph-mgr服务的socket文件存在（这里不存在）且未被进程占用时删除ceph-mgr服务的socket文件
 #  006-001-002-015_skipping task # find ceph rbd mirror socket ,查找ceph-rbd服务的socket文件
 #  006-001-002-016_skipping task # check if the ceph rbd mirror socket is in-use ,rbd服务相关
 #  006-001-002-017_skipping task # remove ceph rbd mirror socket if exists and not used by a process ,rbd服务相关
 #  006-001-002-018_skipping task # check for a nfs ganesha pid ,nfs服务相关
 #  006-001-002-019_skipping task # check for a tcmu-runner ,iscsi服务相关
 #  006-001-002-020_skipping task # check for a rbd-target-api ,iscsi服务相关
 #  006-001-002-021_skipping task # check for a rbd-target-gw ,iscsi服务相关
 #  006-001-002-022_ok task # check for a ceph-crash process ，获取ceph-crash的pid
 #  006-002_ok task # set_fact handler_mon_status ,如果ceph-mon的socket文件存在且被进程在使用则将handler_mon_status设置为true,这里为false
 #  006-003_ok task # set_fact handler_osd_status ,如果ceph-osd的socket文件存在且被进程在使用则将handler_osd_status设置为true,这里为false
 #  006-004_skipping task # set_fact handler_mds_status ,mds相关
 #  006-005_ok task # set_fact handler_rgw_status ,如果ceph-rgw的socket文件存在且被进程在使用则将handler_rgw_status设置为true,这里为false
 #  006-006_skipping task # set_fact handler_nfs_status ,nfs相关
 #  006-007_skipping task # set_fact handler_rbd_status ,rbd相关
 #  006-008_ok task # set_fact handler_mgr_status ,如果ceph-mgr的socket文件存在且被进程在使用则将handler_mgr_status设置为true,这里为false
 #  006-009_ok task # set_fact handler_crash_status ,如果ceph-crash的socket文件存在且被进程在使用则将handler_crash_status设置为true,这里为false
 #  006-010_skipping block # rgw multi-instances related tasks ,rgw多实例相关tasks
 ## 006-010-001 import_role # import_role ceph-config ,导入ceph配置role
 ## 006-010-001-001_skipping include_tasks # include create_ceph_initial_dirs.yml ,容器化部署ceph时导入目录初始化tasks
 ## 006-010-001-002_skipping include_tasks # include_tasks rgw_systemd_environment_file.yml ,?
 ## 006-010-001-003_skipping block # include_tasks config file operations related to OSDs ,?
 ###006-010-001-003-001_skipping task # reset num_osds ,设置osd数量num_osds为0
 ###006-010-001-003-002_skipping task # count number of osds for lvm scenario ,统计osd使用lvm场景的osd数量
 ###006-010-001-003-003_skipping block # 
 ###006-010-001-003-003-001_skipping task # look up for ceph-volume rejected devices, 
 ###006-010-001-003-003-002_skipping task # set_fact rejected_devices, 
 ###006-010-001-003-003-003_skipping task # set_fact _devices, 
 ###006-010-001-003-003-004_skipping task # run 'ceph-volume lvm batch --report' to see how many osds are to be created, 
 ###006-010-001-003-003-005_skipping task # set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report), 
 ###006-010-001-003-003-006_skipping task # set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report), 
 ## 006-010-001-003-004_skipping task # run 'ceph-volume lvm list' to see how many osds have already been created,
 ## 006-010-001-003-005_skipping task # set_fact num_osds (add existing osds),
 #  006-010-001-004_skipping block # create ceph conf directory,?
 #  006-010-001-005_skipping block # "generate {{ cluster }}.conf configuration file",?
 #  006-010-002 import_role # import_role ceph-rgw/pre_requisite.yml ,非容器部署时导入 # ***
 #  006-010-002-001_skipping task # create rgw keyrings ,
 #  006-010-003 import_role # import_role ceph-rgw/multisite.yml ,
 #  006-010-003-001_skipping include_tasks # include_tasks multisite ,
 #  006-010-004 task # set_fact multisite_called_from_handler_role ,

 #  007 import_role # import ceph-validate ,确认各项配置（系统、网络、磁盘、软件仓库等等）
 #  007-001 include_tasks # include check_system.yml ,检查ansible版本，系统版本，服务管理软件是否达到要求的tasks，不满足要求会报错退出
 #  007-001-001_skipping task # fail on unsupported ansible version (1.X) ,ansible主版本小于2时报错,退出playbook执行。
 #  007-001-002_skipping task # fail on unsupported ansible version ,ansible次版本小于9时报错,退出playbook执行。
 #  007-001-003_skipping task # fail on unsupported system, 待执行的主机系统不是linux时报错,退出playbook执行。
 #  007-001-004_skipping task # fail on unsupported architecture, 待执行的主机系统不是x86_64等架构时报错,退出playbook执行。
 #  007-001-005_skipping task # fail on unsupported distribution, 待执行的主机系统不是RedHat、Debian等发行版时报错,退出playbook执行。
 #  007-001-006_skipping task # fail on unsupported CentOS release, 待执行的主机系统是CentOS 7时报错,退出playbook执行。
 #  007-001-007_skipping block # red hat based systems tasks, 待执行的主机系统为RedHat且使用红帽的软件仓库安装ceph时相关tasks,这里跳过
 #  007-001-008_skipping task # fail on unsupported distribution for ubuntu cloud archive, 待执行的主机系统为Ubuntu且使用ubuntu的软件仓库安装ceph时报错,退出playbook执行
 #  007-001-009_skipping task # "fail on unsupported SUSE/openSUSE distribution (only 15.x supported)", 待执行的主机系统为SUSE且主版本为15时报错,退出playbook执行
 #  007-001-010_skipping task # fail if systemd is not present, 待执行主机系统的服务管理程序必须是systemd，否则报错,退出playbook执行
 #  007-002 include_tasks # validate repository variables in non-containerized scenario ,确认非容器部署场景下的仓库配置是否正确
 #  007-002-001_skipping task # validate ceph_origin ,ceph源不是repository、distro、local时报错退出playbook，这里是repository
 #  007-002-002_skipping task # validate ceph_repository ,ceph是repository但是ceph_repository不在community、custom里面时报错退出playbook，这里是ceph_repository是custom
 #  007-002-003_skipping task # validate ceph_repository_community ,ceph是repository且ceph_repository是community，但是ceph版本号不是octopus时报错退出playbook，
 #  007-003_skipping task # validate osd_objectstore ,确认osd存储引擎是bluestor或者filestore，否则报错退出playbook
 #  007-004_skipping task # validate monitor network configuration ,确认ceph-monitor的网络配置无误，否则报错退出playbook
 #  007-005_skipping task # validate radosgw network configuration ,确认radosgw的网络配置无误，否则报错退出playbook
 #  007-006 block # validate osd nodes ,确认osd nodes相关tasks
     #  007-006-001_skipping task # validate lvm osd scenario ,没有开启osd自动发现且没有定义devices同时lvm_volumes也没有定义时报错,退出playbook
     #  007-006-002_skipping task # validate filestore lvm osd scenario ,使用filestore存储引擎时在lvm_volumes定义中必须定义data和journal否则报错,退出playbook
     #  007-006-003_skipping task # validate bluestore lvm osd scenario ,使用bluestore存储引擎时在lvm_volumes定义中必须定义data否则报错,退出playbook
 #  007-007_skipping block # debian based systems tasks ,Debian系统相关的tasks
 #  007-008_skipping block # SUSE/openSUSE Leap based system tasks ,SUSE/openSUSE系统相关的tasks
 #  007-009_skipping task # validate ntp daemon type ,ntp服务的守护进程必须是['chronyd', 'ntpd', 'timesyncd']其中之一，否则报错，退出playbook
 #  007-010_skipping task # validate ntp daemon type ,如果待执行主机的系统是RedHat原子系统，且ntp的守护进程为ntpd，则报错退出palybook
 #  007-011_skipping task # make sure journal_size configured ,osd的存储引擎为filestore时如果journal_size小于5G则打印debug信息。
 #  007-012 include_tasks # include check_devices.yml, 没有开启osd磁盘自动发现时，检查配置的osd盘
 #  007-012-001_ok task # set_fact root_device, 把根盘对应的磁盘赋值给变量root_device
 #  007-012-002_ok block # lvm_volumes variable's tasks related, lvm_volumes变量的相关tasks
     #  007-012-002-001_ok task # resolve devices in lvm_volumes, 解析出lvm_volumes的data盘
     #  007-012-002-002_ok task # set_fact lvm_volumes_data_devices, 设置lvm_volumes data盘
 #  007-012-003_skipping task # fail if root_device is passed in lvm_volumes or devices, 当根盘在lvm_volumes或者devices中时报错退出playbook
 #  007-012-004 block # check devices are block devices, 检查devices都是块设备
     #  007-012-004-001_ok block # get devices information, 获取设备信息
     #  007-012-004-002_skipping block # fail if one of the devices is not a device, 如果有一个设备不是磁盘则报错退出playbook
     #  007-012-004-003_skipping block # fail when gpt header found on osd devices, 如果磁盘头发现gpt分区信息则报错退出playbook
 #  007-012-005_ok block # check logical volume in lvm_volumes, 检查lvm_volumes中的lv
     #  007-012-005-001_skipping task # check data logical volume, 获取vg下的lv的状态，这里vg不存在。
     #  007-012-005-002_skipping task # fail if one of the data logical volume is not a device or doesn't exist, 当逻辑盘不是块设备或者不存在时报错退出playbook
     #  007-012-005-003_skipping task # check bluestore db logical volume, 检查bluestore的db盘
     #  007-012-005-004_skipping task # fail if one of the bluestore db logical volume is not a device or doesn't exist, 当bluestore的db盘不是块设备或者不存在时报错退出playbook
     #  007-012-005-005_skipping task # check bluestore wal logical volume, 检查bluestore的wal盘
     #  007-012-005-006_skipping task # fail if one of the bluestore wal logical volume is not a device or doesn't exist, 当bluestore的wal盘不是块设备或者不存在时报错退出playbook
     #  007-012-005-007_skipping task # check filestore journal logical volume, 检查filestore的journal盘
     #  007-012-005-007_skipping task # fail if one of the filestore journal logical volume is not a device or doesn't exist, 当filestore的journal盘不是块设备或者不存在时报错退出playbook
 #  007-013 include_tasks # include check_eth_mon.yml, 检查ceph-mon的网卡状态及ip地址配置情况，有问题就报错退出playbook
 #  007-013-001_skipping task # "fail if {{ monitor_interface }} does not exist on {{ inventory_hostname }}", monitor_interface不在待执行主机的facts里面时报错，退出playbook
 #  007-013-002_skipping task # "fail if {{ monitor_interface }} is not active on {{ inventory_hostname }}", 待执行主机的monitor_interface不是active状态时报错，退出playbook
 #  007-013-003_skipping task # "fail if {{ monitor_interface }} does not have any ip v4 address on {{ inventory_hostname }}", 待执行主机使用ipv4时monitor_interface没有ipv4地址就报错，退出playbook
 #  007-013-004_skipping task # "fail if {{ monitor_interface }} does not have any ip v6 address on {{ inventory_hostname }}", 待执行主机使用ipv6时monitor_interface没有ipv6地址就报错，退出playbook
 #  007-014 include_tasks # include check_ipaddr_mon.yml, 检查ceph-mon的网卡状态及ip地址配置情况，有问题就报错退出playbook
 #  007-015 include_tasks # include check_eth_rgw.yml, 检查rgw的网卡状态及ip地址配置情况，有问题就报错退出playbook
 #  007-016 include_tasks # include check_rgw_pools.yml, 检查ec（纠删码）rgw pool的配置文件及k和m值是否有配置，有问题就报错退出playbook
 #  007-017 include_tasks # include check_rgw_multisite.yml, 检查rgw mulitsite的配置(masterzone,secondyzone,realm,user,ak/sk)，有问题就报错退出playbook
 #  007-018 include_tasks # include check_iscsi.yml, 检查iscsi的配置，有问题就报错退出playbook
 #  007-019 debug # warn about radosgw_civetweb_num_threads option deprecation, 检查civetweb的线程数配置。
 #  007-020 include_tasks # include check_nfs.yml, 检查nfs相关配置
 #  007-021 include_tasks # include check_rbdmirror.yml, 检查rbdmirror相关配置
 #  007-022 block # check grafana-server config, 启用dashboard时检查grafana-server的配置（组是否存在，组里面是否有主机，密码是否配置）
 #  007-023 fail # validate container registry credentials, ceph-docker 仓库启用认证时，检查认证信息是否配置正确，否则报错退出
 #  007-024 fail # validate container service and container package, 检查容器包名和服务名配置，
 #  007-025 fail # validate openstack_keys key format, 检查openstack keys相关
 #  007-026 fail # validate clients keys key format, 检查client keys格式
 #  007-027 fail # validate openstack_keys caps, 检查openstack keys权限
 #  007-028 fail # validate clients keys key caps, 检查client keys权限
 #  007-029 fail # check virtual_ips is defined, rgwloadbalancer检查虚拟ip的配置
 #  007-030 fail # validate virtual_ips length, rgwloadbalancer检查虚拟ip的个数

 #  008 import_role # import ceph-infra ,配置防火墙、ntp、logrotate
 #  008-001 task # update cache for Debian based OSs ,Debian系统更新apt缓存
 #  008-002 include_tasks # include_tasks configure_firewall.yml ,配置防火墙
 #  008-003 include_tasks # include_tasks setup_ntp.yml ,配置ntp
 #  008-004 task # ensure logrotate is installed ,确保logrotate已安装
 #  008-005 task # add logrotate configuration ,添加logrotate配置

 #  009 import_role # import ceph-common ,配置ceph仓库,安装ceph
 #  009-001 include_tasks # include configure_repository.yml ,配置ceph仓库
 #  009-002 include_tasks # include installs/install_redhat_packages.yml ,redhat系统安装依赖及ceph
 #  009-003 include_tasks # include installs/install_suse_packages.yml ,suse系统安装依赖及ceph
 #  009-004 include_tasks # include installs/install_on_debian.yml ,debian系统安装依赖及ceph
 #  009-005 include_tasks # include_tasks installs/install_on_clear.yml ,ClearLinux系统安装依赖及ceph
 #  009-006 task # get ceph version ,获取ceph版本
 #  009-007 task # set_fact ceph_version ,把获取到的ceph版本赋值给ceph_version
 #  009-008 include_tasks # include release-rhcs.yml, ceph仓库为rhcs/dev同事从发行版安装时设置ceph版本代号
 #  009-008 task # set_fact ceph_release - override ceph_release with ceph_stable_release, ceph仓库不是custom/rhcs/dev时设置ceph版本代号
 #  009-009 include_tasks # include create_rbd_client_dir.yml, 创建rbd client相关目录
 #  009-010 include_tasks # include configure_cluster_name.yml, 配置ceph集群名称
 #  009-011 include_tasks # include configure_memory_allocator.yml, 配置ceph集群各服务内存使用
 #  009-012 include_tasks # include selinux.yml, 配置selinux
