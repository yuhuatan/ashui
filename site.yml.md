 #   准备环境、安装ceph软件 
     所有ceph节点加载配置、检查部署环境、配置网络等、安装ceph软件

 ##  01 检查python环境，没有就安装 [import_tasks  raw_install_python.yml ] 
     ansible管理远程主机依赖于远程主机有python环境, raw_install_python.yml会检查是否python环境是否安装好，没有就安装

 ##  02 获取各主机的facts 
 ##  03 加载部署ceph集群过程中需要的用到的变量 [import_role ceph-defaults]
     ceph集群部署过程中用到的很多变量都定义在ceph-defaults role中，比如ceph集群名称,各个ceph服务组的组名等等

 ##  04 设置facts [import_role ceph-facts] 
     设置一些供后面的role使用的参数，这些参数不能预先定义在ceph-defaults里面，ceph-defaults中都是预先确定的参数，而有些参数需要根据系统配置或者集群状态的信息来确定。比如需要根据系统版本确定容器管理程序是podman还是docker，要根据主机名确定各个monitor节点的monitor_name，要根据部署方式确定ceph服务启动方式是podman run还是ceph，比如后面的ceph-config role需要根据这里设置的一些facts渲染模版文件。确定集群的fsid、crush规则,设置monitor ip、radosgw ip
     设置ceph管理命令（ceph -n client.admin -k /etc/ceph/ceph.client.admin.keyring）
     设置rgw端口、rgw_zone

 ##  05 设置ceph各个服务参数 [import_role ceph-handler]
    检查ceph各个服务的状态，socket文件是否存在，socket文件是否正被进程占用，以及各种ceph相关进程的pid。
    这个role还定义了重启各个ceph服务的tasks，需要时会触发重启各项服务的tasks。

 ##  06 确认配置 [import_role ceph-validate] 
     确认各项配置（系统、网络、磁盘、软件仓库等等）

 ### 检查ansible版本，系统版本，服务管理软件是否达到要求的tasks，不满足要求会报错退出 [include_tasks include check_system.yml]
     ansible主版本小于2时报错,退出playbook执行。
     ansible次版本小于9时报错,退出playbook执行。
     待执行的主机系统不是linux时报错,退出playbook执行。
     待执行的主机系统不是x86_64等架构时报错,退出playbook执行。
     待执行的主机系统不是RedHat、Debian等发行版时报错,退出playbook执行。
     待执行的主机系统是CentOS 7时报错,退出playbook执行。
     待执行的主机系统为RedHat且使用红帽的软件仓库安装ceph时相关tasks,这里跳过
     待执行的主机系统为Ubuntu且使用ubuntu的软件仓库安装ceph时报错,退出playbook执行
     待执行的主机系统为SUSE且主版本为15时报错,退出playbook执行
     待执行主机系统的服务管理程序必须是systemd，否则报错,退出playbook执行

 ### 确认非容器部署场景下的仓库配置是否正确 [include_tasks: check_repository.yml]
     ceph源不是repository、distro、local时报错退出playbook，这里是repository
     ceph是repository但是ceph_repository不在community、custom里面时报错退出playbook，这里是ceph_repository是custom
     ceph是repository且ceph_repository是community，但是ceph版本号不是octopus时报错退出playbook，

 ### 确认osd存储引擎是bluestor或者filestore，否则报错退出playbook [task: validate osd_objectstore]

 ### 确认ceph-monitor的网络配置无误，否则报错退出playbook [task: validate monitor network configuration]

 ### 确认radosgw的网络配置无误，否则报错退出playbook [task: validate radosgw network configuration]

 ### 确认osd nodes相关tasks [block: validate osd nodes]
     没有开启osd自动发现且没有定义devices同时lvm_volumes也没有定义时报错,退出playbook
     使用filestore存储引擎时在lvm_volumes定义中必须定义data和journal否则报错,退出playbook
     使用bluestore存储引擎时在lvm_volumes定义中必须定义data否则报错,退出playbook

 ### Debian系统相关的tasks [block: debian based systems tasks]

 ### SUSE/openSUSE系统相关的tasks [block: SUSE/openSUSE Leap based system tasks]

 ### ntp服务的守护进程必须是('chronyd', 'ntpd', 'timesyncd')其中之一，否则报错，退出playbook [task: validate ntp daemon type]

 ### 如果待执行主机的系统是RedHat原子系统，且ntp的守护进程为ntpd，则报错退出palybook [task: validate ntp daemon type]

 ### osd的存储引擎为filestore时如果journal_size小于5G则打印debug信息 [task: make sure journal_size configured]

 ### 没有开启osd磁盘自动发现时，检查配置的osd盘 [include_tasks: check_devices.yml]
    把根盘对应的磁盘赋值给变量root_device
    lvm_volumes变量的相关tasks
    解析出lvm_volumes的data盘
    设置lvm_volumes data盘
    当根盘在lvm_volumes或者devices中时报错退出playbook
    检查devices都是块设备
    获取设备信息
    如果有一个设备不是磁盘则报错退出playbook
    如果磁盘头发现gpt分区信息则报错退出playbook
    检查lvm_volumes中的lv
    获取vg下的lv的状态，这里vg不存在。
    当逻辑盘不是块设备或者不存在时报错退出playbook
    检查bluestore的db盘
    当bluestore的db盘不是块设备或者不存在时报错退出playbook
    检查bluestore的wal盘
    当bluestore的wal盘不是块设备或者不存在时报错退出playbook
    检查filestore的journal盘
    当filestore的journal盘不是块设备或者不存在时报错退出playbook

 ### 检查ceph-mon的网卡状态及ip地址配置情况，有问题就报错退出playbook [include_tasks: check_eth_mon.yml]
    monitor_interface不在待执行主机的facts里面时报错，退出playbook
    待执行主机的monitor_interface不是active状态时报错，退出playbook
    待执行主机使用ipv4时monitor_interface没有ipv4地址就报错，退出playbook
    待执行主机使用ipv6时monitor_interface没有ipv6地址就报错，退出playbook

 ### 检查ceph-mon的网卡状态及ip地址配置情况，有问题就报错退出playbook [include_tasks: check_ipaddr_mon.yml]

 ### 检查rgw的网卡状态及ip地址配置情况，有问题就报错退出playbook [include_tasks: check_eth_rgw.yml]

 ### 检查ec（纠删码）rgw pool的配置文件及k和m值是否有配置，有问题就报错退出playbook [include_tasks: check_rgw_pools.yml]

 ### 检查rgw mulitsite的配置(masterzone,secondyzone,realm,user,ak/sk)，有问题就报错退出playbook [include_tasks: check_rgw_multisite.yml]

 ### 检查iscsi的配置，有问题就报错退出playbook [include_tasks: check_iscsi.yml]

 ### 检查civetweb的线程数配置 [debug: warn about radosgw_civetweb_num_threads option deprecation]

 ### 检查nfs相关配置 [include_tasks: include check_nfs.yml]

 ### 检查rbdmirror相关配置 [include_tasks: include check_rbdmirror.yml]

 ### 启用dashboard时检查grafana-server的配置（组是否存在，组里面是否有主机，密码是否配置）[block: check grafana-server config]

 ### ceph-docker 仓库启用认证时，检查认证信息是否配置正确，否则报错退出 [fail: validate container registry credentials]

 ### 检查容器包名和服务名配置 [fail: validate container service and container package]

 ### 检查openstack keys相关 [07-25-00 fail # validate openstack_keys key format]

 ### 检查client keys格式 [fail: validate clients keys key format]

 ### 检查openstack keys权限 [fail: validate openstack_keys caps]
 
 ### 检查client keys权限 [fail: validate clients keys key caps]

 ### rgwloadbalancer检查虚拟ip的配置 [fail: check virtual_ips is defined]

 ### rgwloadbalancer检查虚拟ip的个数 [fail: validate virtual_ips length]

 ##  07 配置防火墙、ntp、logrotate [import_role ceph-infra] 

 ### Debian系统更新apt缓存 [task: update cache for Debian based OSs]
 
 ### 配置防火墙 [include_tasks: configure_firewall.yml]

 ### 配置ntp [include_tasks: setup_ntp.yml]

 ### 确保logrotate已安装 [task: ensure logrotate is installed]

 ### 添加logrotate配置 [task: add logrotate configuration]

 ##  08 配置ceph仓库,安装ceph [import_role: ceph-common]
    配置ceph软件包仓库，获取要安装的ceph版本，安装ceph及依赖，配置ceph各服务内存使用，配置selinux。

 ### 配置ceph仓库 [include_tasks: include configure_repository.yml]

 ### redhat系统安装依赖及ceph [include_tasks: include installs/install_redhat_packages.yml]

 ### suse系统安装依赖及ceph [include_tasks: include installs/install_suse_packages.yml]

 ### debian系统安装依赖及ceph [include_tasks: include installs/install_on_debian.yml]

 ### ClearLinux系统安装依赖及ceph [include_tasks: include_tasks installs/install_on_clear.yml]

 ### 获取ceph版本 [task: get ceph version]

 ### 把获取到的ceph版本赋值给ceph_version [task: set_fact ceph_version]

 ### ceph仓库为rhcs/dev同事从发行版安装时设置ceph版本代号 [include_tasks: include release-rhcs.yml]
 
 ### ceph仓库不是custom/rhcs/dev时设置ceph版本代号 [task: set_fact ceph_release - override ceph_release with ceph_stable_release]

 ### 创建rbd client相关目录 [include_tasks: create_rbd_client_dir.yml]
 
 ### 配置ceph集群名称 [include_tasks: include configure_cluster_name.yml]

 ### 配置ceph集群各服务内存使用 [include_tasks: include configure_memory_allocator.yml]

 ### 配置selinux [include_tasks: include selinux.yml]

 #   部署monitor
 ##  加载默认配置 [import_role ceph-defaults]
 ##  设置facts [import_role ceph-facts]
 ### 加载facts.yml
     设置一些供后面的role使用的参数，这些参数不能预先定义在ceph-defaults里面，ceph-defaults中都是预先确定的参数，而有些参数需要根据系统配置或者集群状态的信息来确定。比如需要根据系统版本确定容器管理程序是podman还是docker，要根据主机名确定各个monitor节点的monitor_name，要根据部署方式确定ceph服务启动方式是podman run还是ceph，比如后面的ceph-config role需要根据这里设置的一些facts渲染模版文件。确定集群的fsid、crush规则,设置monitor ip、radosgw ip
     设置ceph管理命令（ceph -n client.admin -k /etc/ceph/ceph.client.admin.keyring）
     设置rgw端口、rgw_zone
 ##  检查ceph各项服务状态[import_role ceph-handler]
    检查服务状态，触发重启ceph各项服务。
 ##  生成配置文件 [import_role ceph-config]
    创建ceph目录（/etc/ceph，/var/lib/ceph 等），根据配置渲染生成配置文件。
 ##  部署启动monitor [import_role ceph-mon]
    确认monitor初始化keyring，初始化monitor目录(包括权限等),初始化monitor，启动monitor，安全加固等。
 #   部署mgr
 ##  加载默认配置 [import_role ceph-defaults]
 ##  设置facts [import_role ceph-facts]
 ##  检查ceph各项服务状态 [import_role ceph-handler]
 ##  生成配置文件 [import_role ceph-config]
 ##  部署启动mgr [import_role ceph-mgr]

 #   部署osd
 ##  加载默认配置 [import_role ceph-defaults]
 ##  设置facts [import_role ceph-facts]
 ##  检查ceph各项服务状态 [import_role ceph-handler]
 ##  生成配置文件 [import_role ceph-config]
 ##  部署启动osd [import_role ceph-mgr]

 #   部署rgw
 ##  加载默认配置 [import_role ceph-defaults]
 ##  设置facts [import_role ceph-facts]
 ##  检查ceph各项服务状态 [import_role ceph-handler]
 ##  生成配置文件 [import_role ceph-config]
 ##  部署启动rgw [import_role ceph-mgr]

 #   部署clients [跳过]
 #   部署nfss [跳过]
 #   部署rbdmirrors [跳过]
 #   部署iscsigws,iscsi-gws [跳过]
 #   部署rgwloadbalancers [跳过]

 #   部署dashboard [import_playbook: dashboard.yml]
    PLAY [mons,osds,mdss,rgws,mgrs,rbdmirrors,nfss,iscsigws,grafana-server]
 ##  部署node exporter
 ### 加载默认配置 [import_role ceph-defaults]
 ### 设置facts [import_role ceph-facts]
 ### [import_role ceph-container-engine]
   #安装配置容器引擎相关(podman/docker)
 ### [import_role ceph-container-common]
   #部署dashboard相关容器
 ### [import_role ceph-node-exporter]
    部署启动node-exporter容器
 ##  部署grafana_server 
 ### 加载默认配置 [import_role ceph-defaults]
 ### 设置facts [import_role ceph-facts]
 ### 部署prometheus [import_role ceph-prometheus]
 ### 部署grafana [import_role ceph-grafana]
 ##  部署dashboard
 ### 加载默认配置 [import_role ceph-defaults]
 ### 设置facts [import_role ceph-facts]
 ### 部署dashboard [import_role ceph-dashboard]
    安装部署配置dashboard

 #   部署ceph crash
 ##  加载默认配置 [import_role ceph-defaults]
 ##  设置facts [import_role ceph-facts]
 ##  检查ceph各项服务状态 [import_role ceph-handler]
 ##  部署ceph crash [import_playbook: ceph-crash]

 #   获取ceph集群状态并打印