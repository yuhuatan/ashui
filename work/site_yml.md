 # PLAY [mons,osds,mdss,rgws,nfss,rbdmirrors,clients,mgrs,iscsigws,iscsi-gws,grafana-server,rgwloadbalancers] ***
 ## TASK [check for python] ***
 ok: [cepht2] => (item=/usr/bin/python)
 ok: [cepht5] => (item=/usr/bin/python)
 ok: [cepht4] => (item=/usr/bin/python)
 ok: [cepht1] => (item=/usr/bin/python)
 ok: [cepht3] => (item=/usr/bin/python)
 ok: [cepht2] => (item=/usr/bin/python3)
 ok: [cepht4] => (item=/usr/bin/python3)
 ok: [cepht5] => (item=/usr/bin/python3)
 ok: [cepht1] => (item=/usr/bin/python3)
 ok: [cepht3] => (item=/usr/bin/python3)
 ok: [cepht1] => (item=/usr/libexec/platform-python)
 ok: [cepht2] => (item=/usr/libexec/platform-python)
 ok: [cepht5] => (item=/usr/libexec/platform-python)
 ok: [cepht4] => (item=/usr/libexec/platform-python)
 ok: [cepht3] => (item=/usr/libexec/platform-python)
 ## TASK [check for dnf-3 package manager (RedHat/Fedora/CentOS)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [check for yum package manager (RedHat/Fedora/CentOS)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [check for apt package manager (Debian/Ubuntu)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [check for zypper package manager (SUSE/OpenSUSE)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [install python for RedHat based OS - dnf] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [install python for debian based OS] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [install python for SUSE/OpenSUSE] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [install python-xml for opensuse only if python2 is installed already] ***
 skipping: [cepht1] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python3', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'stat': {'exists': True, 'path': '/usr/libexec/platform-python', 'mode': '0777', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': True, 'issock': False, 'uid': 0, 'gid': 0, 'size': 20, 'inode': 134641988, 'dev': 2051, 'nlink': 1, 'atime': 1642496803.197162, 'mtime': 1598291968.0, 'ctime': 1608805258.4367108, 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': True, 'rgrp': True, 'xgrp': True, 'woth': True, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False, 'blocks': 0, 'block_size': 4096, 'device_type': 0, 'readable': True, 'writeable': True, 'executable': True, 'lnk_source': '/usr/libexec/platform-python3.6', 'lnk_target': './platform-python3.6', 'pw_name': 'root', 'gr_name': 'root', 'mimetype': 'inode/symlink', 'charset': 'binary', 'version': None, 'attributes': [], 'attr_flags': ''}, 'invocation': {'module_args': {'path': '/usr/libexec/platform-python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/libexec/platform-python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python3', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'stat': {'exists': True, 'path': '/usr/libexec/platform-python', 'mode': '0777', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': True, 'issock': False, 'uid': 0, 'gid': 0, 'size': 20, 'inode': 134641988, 'dev': 2051, 'nlink': 1, 'atime': 1642496797.305702, 'mtime': 1598291968.0, 'ctime': 1608805258.4367108, 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': True, 'rgrp': True, 'xgrp': True, 'woth': True, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False, 'blocks': 0, 'block_size': 4096, 'device_type': 0, 'readable': True, 'writeable': True, 'executable': True, 'lnk_source': '/usr/libexec/platform-python3.6', 'lnk_target': './platform-python3.6', 'pw_name': 'root', 'gr_name': 'root', 'mimetype': 'inode/symlink', 'charset': 'binary', 'version': None, 'attributes': [], 'attr_flags': ''}, 'invocation': {'module_args': {'path': '/usr/libexec/platform-python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/libexec/platform-python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python3', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'stat': {'exists': True, 'path': '/usr/libexec/platform-python', 'mode': '0777', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': True, 'issock': False, 'uid': 0, 'gid': 0, 'size': 20, 'inode': 134641988, 'dev': 2051, 'nlink': 1, 'atime': 1642496802.962331, 'mtime': 1598291968.0, 'ctime': 1608805258.4367108, 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': True, 'rgrp': True, 'xgrp': True, 'woth': True, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False, 'blocks': 0, 'block_size': 4096, 'device_type': 0, 'readable': True, 'writeable': True, 'executable': True, 'lnk_source': '/usr/libexec/platform-python3.6', 'lnk_target': './platform-python3.6', 'pw_name': 'root', 'gr_name': 'root', 'mimetype': 'inode/symlink', 'charset': 'binary', 'version': None, 'attributes': [], 'attr_flags': ''}, 'invocation': {'module_args': {'path': '/usr/libexec/platform-python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/libexec/platform-python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python3', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'stat': {'exists': True, 'path': '/usr/libexec/platform-python', 'mode': '0777', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': True, 'issock': False, 'uid': 0, 'gid': 0, 'size': 20, 'inode': 134641988, 'dev': 2051, 'nlink': 1, 'atime': 1642496802.972374, 'mtime': 1598291968.0, 'ctime': 1608805258.4367108, 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': True, 'rgrp': True, 'xgrp': True, 'woth': True, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False, 'blocks': 0, 'block_size': 4096, 'device_type': 0, 'readable': True, 'writeable': True, 'executable': True, 'lnk_source': '/usr/libexec/platform-python3.6', 'lnk_target': './platform-python3.6', 'pw_name': 'root', 'gr_name': 'root', 'mimetype': 'inode/symlink', 'charset': 'binary', 'version': None, 'attributes': [], 'attr_flags': ''}, 'invocation': {'module_args': {'path': '/usr/libexec/platform-python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/libexec/platform-python', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'stat': {'exists': False}, 'invocation': {'module_args': {'path': '/usr/bin/python3', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/bin/python3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'stat': {'exists': True, 'path': '/usr/libexec/platform-python', 'mode': '0777', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': True, 'issock': False, 'uid': 0, 'gid': 0, 'size': 20, 'inode': 134641988, 'dev': 2051, 'nlink': 1, 'atime': 1642496802.43316, 'mtime': 1598291968.0, 'ctime': 1608805258.4367108, 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': True, 'rgrp': True, 'xgrp': True, 'woth': True, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False, 'blocks': 0, 'block_size': 4096, 'device_type': 0, 'readable': True, 'writeable': True, 'executable': True, 'lnk_source': '/usr/libexec/platform-python3.6', 'lnk_target': './platform-python3.6', 'pw_name': 'root', 'gr_name': 'root', 'mimetype': 'inode/symlink', 'charset': 'binary', 'version': None, 'attributes': [], 'attr_flags': ''}, 'invocation': {'module_args': {'path': '/usr/libexec/platform-python', 'follow': False, 'get_md5': False, 'get_checksum': True, 'get_mime': True, 'get_attributes': True, 'checksum_algorithm': 'sha1'}}, 'failed': False, 'failed_when_result': False, 'item': '/usr/libexec/platform-python', 'ansible_loop_var': 'item'}) 
 ## TASK [gather facts] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [gather and delegate facts] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [create filtered clients group] ***
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:16.416026', 'end': '2022-01-18 17:11:16.423034', 'delta': '0:00:00.007008', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:16.642945', 'end': '2022-01-18 17:11:16.650005', 'delta': '0:00:00.007060', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:16.867495', 'end': '2022-01-18 17:11:16.874514', 'delta': '0:00:00.007019', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:17.095284', 'end': '2022-01-18 17:11:17.100104', 'delta': '0:00:00.004820', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:17.321596', 'end': '2022-01-18 17:11:17.328638', 'delta': '0:00:00.007042', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:16.416026', 'end': '2022-01-18 17:11:16.423034', 'delta': '0:00:00.007008', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:16.642945', 'end': '2022-01-18 17:11:16.650005', 'delta': '0:00:00.007060', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:16.867495', 'end': '2022-01-18 17:11:16.874514', 'delta': '0:00:00.007019', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:17.095284', 'end': '2022-01-18 17:11:17.100104', 'delta': '0:00:00.004820', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:11:17.321596', 'end': '2022-01-18 17:11:17.328638', 'delta': '0:00:00.007042', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final devices list] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht5]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht2]
 skipping: [cepht1]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 ok: [cepht2] => (item=cepht1)
 ok: [cepht1] => (item=cepht1)
 ok: [cepht3] => (item=cepht1)
 ok: [cepht4] => (item=cepht1)
 ok: [cepht3] => (item=cepht2)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht3] => (item=cepht3)
 ok: [cepht2] => (item=cepht2)
 ok: [cepht2] => (item=cepht3)
 ok: [cepht2] => (item=cepht4)
 ok: [cepht2] => (item=cepht5)
 ok: [cepht5] => (item=cepht1)
 ok: [cepht4] => (item=cepht2)
 ok: [cepht4] => (item=cepht3)
 ok: [cepht3] => (item=cepht4)
 ok: [cepht3] => (item=cepht5)
 ok: [cepht4] => (item=cepht4)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht5] => (item=cepht2)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht4] => (item=cepht5)
 ok: [cepht5] => (item=cepht3)
 ok: [cepht1] => (item=cepht5)
 ok: [cepht5] => (item=cepht4)
 ok: [cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 ok: [cepht1] => (item=0)
 ok: [cepht1] => (item=1)
 ok: [cepht2] => (item=0)
 ok: [cepht2] => (item=1)
 ok: [cepht3] => (item=0)
 ok: [cepht3] => (item=1)
 ok: [cepht4] => (item=0)
 ok: [cepht5] => (item=0)
 ok: [cepht4] => (item=1)
 ok: [cepht5] => (item=1)
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht3]
 ok: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 ok: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-handler : include check_running_containers.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : include check_socket_non_container.yml] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/check_socket_non_container.yml for cepht1, cepht3, cepht2, cepht4, cepht5
 ## TASK [ceph-handler : find ceph mon socket] ***
 ok: [cepht5]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht1]
 ## TASK [ceph-handler : check if the ceph mon socket is in-use] ***
 ## TASK [ceph-handler : remove ceph mon socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph osd socket] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph osd socket is in-use] ***
 ## TASK [ceph-handler : remove ceph osd socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph osd socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph mds socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph mds socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : find ceph rgw socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-handler : check if the ceph rgw socket is in-use] ***
 ## TASK [ceph-handler : remove ceph rgw socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph mgr socket] ***
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht3]
 ok: [cepht2]
 ## TASK [ceph-handler : check if the ceph mgr socket is in-use] ***
 ## TASK [ceph-handler : remove ceph mgr socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph rbd mirror socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph rbd mirror socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph rbd mirror socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a nfs ganesha pid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a tcmu-runner] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-api] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-gw] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a ceph-crash process] ***
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht1]
 ok: [cepht3]
 ## TASK [ceph-handler : set_fact handler_mon_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_osd_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mds_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rgw_status] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_nfs_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rbd_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mgr_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_crash_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : reset num_osds] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : create ceph conf directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : create rgw keyrings] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht1] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht2] => (item=None) 
 ## TASK [ceph-rgw : include_tasks multisite] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact multisite_called_from_handler_role] ***
 skipping: [cepht1]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 ## TASK [ceph-validate : include check_system.yml] ***
 included: /ceph-ansible/roles/ceph-validate/tasks/check_system.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-validate : fail on unsupported ansible version (1.X)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail on unsupported ansible version] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail on unsupported system] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail on unsupported architecture] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : fail on unsupported distribution] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : fail on unsupported CentOS release] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail on unsupported distribution for red hat ceph storage] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : determine if node is registered with subscription-manager] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail on unregistered red hat rhcs linux] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail on unsupported distribution for ubuntu cloud archive] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : fail on unsupported SUSE/openSUSE distribution (only 15.x supported)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail if systemd is not present] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate repository variables in non-containerized scenario] ***
 included: /ceph-ansible/roles/ceph-validate/tasks/check_repository.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-validate : validate ceph_origin] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate ceph_repository] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : validate ceph_repository_community] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate osd_objectstore] ***
 skipping: [cepht2]
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate monitor network configuration] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : validate radosgw network configuration] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate lvm osd scenario] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate filestore lvm osd scenario] ***
 skipping: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 ## TASK [ceph-validate : validate bluestore lvm osd scenario] ***
 skipping: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 ## TASK [ceph-validate : fail if local scenario is enabled on debian] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail if rhcs repository is enabled on debian] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : Check ceph_origin definition on SUSE/openSUSE Leap] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : Check ceph_repository definition on SUSE/openSUSE Leap] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate ntp daemon type] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : abort if ntp_daemon_type is ntpd on Atomic] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : make sure journal_size configured] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : include check_devices.yml] ***
 included: /ceph-ansible/roles/ceph-validate/tasks/check_devices.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-validate : set_fact root_device] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-validate : resolve devices in lvm_volumes] ***
 ok: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 ok: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 ok: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 ok: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 ok: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 ok: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 ok: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 ok: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 ok: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 ok: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 ## TASK [ceph-validate : set_fact lvm_volumes_data_devices] ***
 ok: [cepht1] => (item={'cmd': ['readlink', '-f', '/dev/sdb'], 'stdout': '/dev/sdb', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.517873', 'end': '2022-01-18 17:11:28.537813', 'delta': '0:00:00.019940', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdb', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdb'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['readlink', '-f', '/dev/sdd'], 'stdout': '/dev/sdd', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.759488', 'end': '2022-01-18 17:11:28.762945', 'delta': '0:00:00.003457', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdd', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdd'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'})
 ok: [cepht2] => (item={'cmd': ['readlink', '-f', '/dev/sdb'], 'stdout': '/dev/sdb', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.533083', 'end': '2022-01-18 17:11:28.552990', 'delta': '0:00:00.019907', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdb', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdb'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'})
 ok: [cepht2] => (item={'cmd': ['readlink', '-f', '/dev/sdd'], 'stdout': '/dev/sdd', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.776528', 'end': '2022-01-18 17:11:28.780089', 'delta': '0:00:00.003561', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdd', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdd'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'})
 ok: [cepht3] => (item={'cmd': ['readlink', '-f', '/dev/sdb'], 'stdout': '/dev/sdb', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.536199', 'end': '2022-01-18 17:11:28.556545', 'delta': '0:00:00.020346', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdb', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdb'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'})
 ok: [cepht3] => (item={'cmd': ['readlink', '-f', '/dev/sdd'], 'stdout': '/dev/sdd', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.779152', 'end': '2022-01-18 17:11:28.782681', 'delta': '0:00:00.003529', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdd', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdd'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'})
 ok: [cepht4] => (item={'cmd': ['readlink', '-f', '/dev/sdb'], 'stdout': '/dev/sdb', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.549572', 'end': '2022-01-18 17:11:28.568908', 'delta': '0:00:00.019336', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdb', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdb'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'})
 ok: [cepht5] => (item={'cmd': ['readlink', '-f', '/dev/sdb'], 'stdout': '/dev/sdb', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.546579', 'end': '2022-01-18 17:11:28.565793', 'delta': '0:00:00.019214', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdb', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdb'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'})
 ok: [cepht4] => (item={'cmd': ['readlink', '-f', '/dev/sdd'], 'stdout': '/dev/sdd', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.780579', 'end': '2022-01-18 17:11:28.784079', 'delta': '0:00:00.003500', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdd', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdd'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'})
 ok: [cepht5] => (item={'cmd': ['readlink', '-f', '/dev/sdd'], 'stdout': '/dev/sdd', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:11:28.772842', 'end': '2022-01-18 17:11:28.776371', 'delta': '0:00:00.003529', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'readlink -f /dev/sdd', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/dev/sdd'], 'stderr_lines': [], 'failed': False, 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-validate : fail if root_device is passed in lvm_volumes or devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : get devices information] ***
 ok: [cepht2] => (item=/dev/sdb)
 ok: [cepht4] => (item=/dev/sdb)
 ok: [cepht3] => (item=/dev/sdb)
 ok: [cepht5] => (item=/dev/sdb)
 ok: [cepht1] => (item=/dev/sdb)
 ok: [cepht4] => (item=/dev/sdd)
 ok: [cepht3] => (item=/dev/sdd)
 ok: [cepht2] => (item=/dev/sdd)
 ok: [cepht5] => (item=/dev/sdd)
 ok: [cepht1] => (item=/dev/sdd)
 ## TASK [ceph-validate : fail if one of the devices is not a device] ***
 skipping: [cepht1] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-validate : fail when gpt header found on osd devices] ***
 skipping: [cepht1] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'disk': {'dev': '/dev/sdb', 'size': 131072.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdb', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdb', 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'disk': {'dev': '/dev/sdd', 'size': 524288.0, 'unit': 'mib', 'table': 'unknown', 'model': 'VMware Virtual disk', 'logical_block': 512, 'physical_block': 512}, 'partitions': [], 'script': "unit 'MiB' print", 'invocation': {'module_args': {'device': '/dev/sdd', 'unit': 'MiB', 'align': 'optimal', 'label': 'msdos', 'part_type': 'primary', 'part_start': '0%', 'part_end': '100%', 'state': 'info', 'number': None, 'name': None, 'flags': None}}, 'failed': False, 'failed_when_result': False, 'item': '/dev/sdd', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-validate : check data logical volume] ***
 skipping: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 ## TASK [ceph-validate : fail if one of the data logical volume is not a device or doesn't exist] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-validate : check bluestore db logical volume] ***
 skipping: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 ## TASK [ceph-validate : fail if one of the bluestore db logical volume is not a device or doesn't exist] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-validate : check bluestore wal logical volume] ***
 skipping: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 ## TASK [ceph-validate : fail if one of the bluestore wal logical volume is not a device or doesn't exist] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-validate : check filestore journal logical volume] ***
 skipping: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'}) 
 skipping: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'}) 
 ## TASK [ceph-validate : fail if one of the filestore journal logical volume is not a device or doesn't exist] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht2] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht3] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdb', 'crush_device_class': 'ssd'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht5] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'data': '/dev/sdd', 'crush_device_class': 'hdd'}, 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-validate : include check_eth_mon.yml] ***
 included: /ceph-ansible/roles/ceph-validate/tasks/check_eth_mon.yml for cepht1, cepht3, cepht2, cepht5, cepht4
 ## TASK [ceph-validate : fail if ens192 does not exist on cepht1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail if ens192 is not active on cepht1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail if ens192 does not have any ip v4 address on cepht1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail if ens192 does not have any ip v6 address on cepht1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : include check_ipaddr_mon.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : include check_eth_rgw.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : include check_rgw_pools.yml] ***
 included: /ceph-ansible/roles/ceph-validate/tasks/check_rgw_pools.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-validate : fail if ec_profile is not set for ec pools] ***
 skipping: [cepht1] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht2] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht5] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht3] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht4] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 ## TASK [ceph-validate : fail if ec_k is not set for ec pools] ***
 skipping: [cepht1] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht2] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht4] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht3] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht5] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 ## TASK [ceph-validate : fail if ec_m is not set for ec pools] ***
 skipping: [cepht1] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht2] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht4] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht3] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 skipping: [cepht5] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}}) 
 ## TASK [ceph-validate : include check_rgw_multisite.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : include check_iscsi.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : warn about radosgw_civetweb_num_threads option deprecation] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : include check_nfs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : include check_rbdmirror.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail if [grafana-server] group doesn't exist] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail when [grafana-server] doesn't contain at least one node.] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : fail when dashboard_admin_password and/or grafana_admin_password are not set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate container registry credentials] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate container service and container package] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : validate openstack_keys key format] ***
 skipping: [cepht1] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 ## TASK [ceph-validate : validate clients keys key format] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-validate : validate openstack_keys caps] ***
 skipping: [cepht1] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht1] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht2] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.glance', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.cinder', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=volumes, profile rbd pool=vms, profile rbd pool=images'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.cinder-backup', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht4] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.gnocchi', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=metrics'}, 'mode': '0600'}) 
 skipping: [cepht3] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 skipping: [cepht5] => (item={'name': 'client.openstack', 'caps': {'mon': 'profile rbd', 'osd': 'profile rbd pool=images, profile rbd pool=vms, profile rbd pool=volumes, profile rbd pool=backups'}, 'mode': '0600'}) 
 ## TASK [ceph-validate : validate clients keys caps] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : check virtual_ips is defined] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-validate : validate virtual_ips length] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : update cache for Debian based OSs] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : include_tasks configure_firewall.yml] ***
 included: /ceph-ansible/roles/ceph-infra/tasks/configure_firewall.yml for cepht1, cepht2, cepht4, cepht3, cepht5
 ## TASK [ceph-infra : check firewalld installation on redhat or SUSE/openSUSE] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht3]
 ## TASK [ceph-infra : install firewalld python binding] ***
 ok: [cepht5]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ## TASK [ceph-infra : start firewalld] ***
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht5]
 ## TASK [ceph-infra : open ceph networks on monitor] ***
 changed: [cepht1] => (item=192.168.0.0/16)
 changed: [cepht2] => (item=192.168.0.0/16)
 changed: [cepht3] => (item=192.168.0.0/16)
 changed: [cepht4] => (item=192.168.0.0/16)
 changed: [cepht5] => (item=192.168.0.0/16)
 ## TASK [ceph-infra : open ceph networks on manager when collocated] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open monitor and manager ports] ***
 changed: [cepht1] => (item={'service': 'ceph-mon', 'zone': 'public'})
 changed: [cepht5] => (item={'service': 'ceph-mon', 'zone': 'public'})
 changed: [cepht2] => (item={'service': 'ceph-mon', 'zone': 'public'})
 changed: [cepht4] => (item={'service': 'ceph-mon', 'zone': 'public'})
 changed: [cepht3] => (item={'service': 'ceph-mon', 'zone': 'public'})
 changed: [cepht2] => (item={'service': 'ceph', 'zone': 'public'})
 changed: [cepht1] => (item={'service': 'ceph', 'zone': 'public'})
 changed: [cepht4] => (item={'service': 'ceph', 'zone': 'public'})
 changed: [cepht3] => (item={'service': 'ceph', 'zone': 'public'})
 changed: [cepht5] => (item={'service': 'ceph', 'zone': 'public'})
 ## TASK [ceph-infra : open ceph networks on manager when dedicated] ***
 ok: [cepht1] => (item=192.168.0.0/16)
 ok: [cepht2] => (item=192.168.0.0/16)
 ok: [cepht4] => (item=192.168.0.0/16)
 ok: [cepht3] => (item=192.168.0.0/16)
 ok: [cepht5] => (item=192.168.0.0/16)
 ## TASK [ceph-infra : open manager ports] ***
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht5]
 ## TASK [ceph-infra : open ceph networks on osd] ***
 ok: [cepht1] => (item=192.168.0.0/16)
 ok: [cepht2] => (item=192.168.0.0/16)
 ok: [cepht3] => (item=192.168.0.0/16)
 ok: [cepht5] => (item=192.168.0.0/16)
 ok: [cepht4] => (item=192.168.0.0/16)
 changed: [cepht1] => (item=172.172.172.0/24)
 changed: [cepht2] => (item=172.172.172.0/24)
 changed: [cepht3] => (item=172.172.172.0/24)
 changed: [cepht4] => (item=172.172.172.0/24)
 changed: [cepht5] => (item=172.172.172.0/24)
 ## TASK [ceph-infra : open osd ports] ***
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht1]
 ## TASK [ceph-infra : open ceph networks on rgw] ***
 ok: [cepht1] => (item=192.168.0.0/16)
 ok: [cepht3] => (item=192.168.0.0/16)
 ok: [cepht2] => (item=192.168.0.0/16)
 ok: [cepht5] => (item=192.168.0.0/16)
 ok: [cepht4] => (item=192.168.0.0/16)
 ## TASK [ceph-infra : open rgw ports] ***
 changed: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-infra : open ceph networks on mds] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open mds ports] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open ceph networks on nfs] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open nfs ports] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : open nfs ports (portmapper)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : open ceph networks on rbdmirror] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open rbdmirror ports] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : open ceph networks on iscsi] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open iscsi target ports] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : open iscsi api ports] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-infra : open iscsi/prometheus port] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : open dashboard ports] ***
 included: /ceph-ansible/roles/ceph-infra/tasks/dashboard_firewall.yml for cepht1, cepht3, cepht2, cepht5, cepht4
 ## TASK [ceph-infra : open node_exporter port] ***
 changed: [cepht1]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht5]
 changed: [cepht3]
 ## TASK [ceph-infra : open dashboard port] ***
 changed: [cepht1]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht3]
 changed: [cepht5]
 ## TASK [ceph-infra : open mgr/prometheus port] ***
 changed: [cepht2]
 changed: [cepht3]
 changed: [cepht5]
 changed: [cepht1]
 changed: [cepht4]
 ## TASK [ceph-infra : open grafana port] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 changed: [cepht4]
 ## TASK [ceph-infra : open prometheus port] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 changed: [cepht4]
 ## TASK [ceph-infra : open alertmanager port] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 changed: [cepht4]
 ## TASK [ceph-infra : open alertmanager cluster port] ***
 skipping: [cepht1] => (item=tcp) 
 skipping: [cepht1] => (item=udp) 
 skipping: [cepht2] => (item=tcp) 
 skipping: [cepht2] => (item=udp) 
 skipping: [cepht3] => (item=tcp) 
 skipping: [cepht3] => (item=udp) 
 skipping: [cepht5] => (item=tcp) 
 skipping: [cepht5] => (item=udp) 
 changed: [cepht4] => (item=tcp)
 changed: [cepht4] => (item=udp)
 ## TASK [ceph-infra : open ceph networks on haproxy] ***
 skipping: [cepht1] => (item=192.168.0.0/16) 
 skipping: [cepht2] => (item=192.168.0.0/16) 
 skipping: [cepht3] => (item=192.168.0.0/16) 
 skipping: [cepht4] => (item=192.168.0.0/16) 
 skipping: [cepht5] => (item=192.168.0.0/16) 
 ## TASK [ceph-infra : open haproxy ports] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : add rich rule for keepalived vrrp] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-infra : include_tasks setup_ntp.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : ensure logrotate is installed] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-infra : add logrotate configuration] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include configure_repository.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/configure_repository.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-common : include installs/configure_redhat_repository_installation.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/installs/configure_redhat_repository_installation.yml for cepht2, cepht1, cepht3, cepht4, cepht5
 ## TASK [ceph-common : include redhat_community_repository.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-common : include redhat_rhcs_repository.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include redhat_dev_repository.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include redhat_custom_repository.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/installs/redhat_custom_repository.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-common : configure red hat custom rpm key] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-common : configure red hat custom repository] ***
 changed: [cepht1]
 changed: [cepht2]
 changed: [cepht3]
 changed: [cepht4]
 changed: [cepht5]
 ## TASK [ceph-common : purge yum cache] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include installs/configure_redhat_local_installation.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include installs/configure_debian_repository_installation.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : update apt cache if cache_valid_time has expired] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include installs/configure_suse_repository_installation.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include installs/install_redhat_packages.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/installs/install_redhat_packages.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-common : install redhat dependencies] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : install centos dependencies] ***
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-common : install redhat ceph packages] ***
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht5]
 changed: [cepht4]
 changed: [cepht2]
 ## TASK [ceph-common : include installs/install_suse_packages.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include installs/install_on_debian.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-common : include_tasks installs/install_on_clear.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : get ceph version] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-common : set_fact ceph_version] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-common : include release-rhcs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : set_fact ceph_release - override ceph_release with ceph_stable_release] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include create_rbd_client_dir.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/create_rbd_client_dir.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-common : create rbd client directory] ***
 ok: [cepht2] => (item=/var/run/ceph)
 ok: [cepht1] => (item=/var/run/ceph)
 ok: [cepht3] => (item=/var/run/ceph)
 ok: [cepht5] => (item=/var/run/ceph)
 ok: [cepht4] => (item=/var/run/ceph)
 changed: [cepht1] => (item=/var/log/ceph)
 changed: [cepht3] => (item=/var/log/ceph)
 changed: [cepht5] => (item=/var/log/ceph)
 changed: [cepht4] => (item=/var/log/ceph)
 changed: [cepht2] => (item=/var/log/ceph)
 ## TASK [ceph-common : include configure_cluster_name.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/configure_cluster_name.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-common : configure cluster name] ***
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht5]
 changed: [cepht2]
 changed: [cepht4]
 ## TASK [ceph-common : check /etc/default/ceph exist] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : when /etc/default/ceph is not dir] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : when /etc/default/ceph is dir] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : include configure_memory_allocator.yml] ***
 included: /ceph-ansible/roles/ceph-common/tasks/configure_memory_allocator.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-common : configure TCMALLOC_MAX_TOTAL_THREAD_CACHE_BYTES for debian] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-common : configure TCMALLOC_MAX_TOTAL_THREAD_CACHE_BYTES for redhat] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-common : include selinux.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 # PLAY [mons] ***
 ## TASK [set ceph monitor install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ok: [cepht2]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:47.477487', 'end': '2022-01-18 17:12:47.484481', 'delta': '0:00:00.006994', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:47.703786', 'end': '2022-01-18 17:12:47.711229', 'delta': '0:00:00.007443', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:47.933291', 'end': '2022-01-18 17:12:47.940449', 'delta': '0:00:00.007158', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:48.149063', 'end': '2022-01-18 17:12:48.155537', 'delta': '0:00:00.006474', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:48.368610', 'end': '2022-01-18 17:12:48.375664', 'delta': '0:00:00.007054', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:47.477487', 'end': '2022-01-18 17:12:47.484481', 'delta': '0:00:00.006994', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:47.703786', 'end': '2022-01-18 17:12:47.711229', 'delta': '0:00:00.007443', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:47.933291', 'end': '2022-01-18 17:12:47.940449', 'delta': '0:00:00.007158', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:48.149063', 'end': '2022-01-18 17:12:48.155537', 'delta': '0:00:00.006474', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': {'msg': 'non-zero return code', 'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '', 'stderr': "stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory", 'rc': 1, 'start': '2022-01-18 17:12:48.368610', 'end': '2022-01-18 17:12:48.375664', 'delta': '0:00:00.007054', 'changed': False, 'failed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': ["stat: cannot stat '/var/run/ceph/ceph-mon*.asok': No such file or directory"], 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-handler : include check_running_containers.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : include check_socket_non_container.yml] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/check_socket_non_container.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-handler : find ceph mon socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht3]
 ## TASK [ceph-handler : check if the ceph mon socket is in-use] ***
 ## TASK [ceph-handler : remove ceph mon socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph osd socket] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-handler : check if the ceph osd socket is in-use] ***
 ## TASK [ceph-handler : remove ceph osd socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph osd socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph mds socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph mds socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : find ceph rgw socket] ***
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph rgw socket is in-use] ***
 ## TASK [ceph-handler : remove ceph rgw socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph mgr socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht3]
 ## TASK [ceph-handler : check if the ceph mgr socket is in-use] ***
 ## TASK [ceph-handler : remove ceph mgr socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph rbd mirror socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph rbd mirror socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph rbd mirror socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a nfs ganesha pid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a tcmu-runner] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-api] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-gw] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a ceph-crash process] ***
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mon_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_osd_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mds_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rgw_status] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-handler : set_fact handler_nfs_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rbd_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mgr_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_crash_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : reset num_osds] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-rgw : create rgw keyrings] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht1] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht4] => (item=None) 
 ## TASK [ceph-rgw : include_tasks multisite] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact multisite_called_from_handler_role] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 included: /ceph-ansible/roles/ceph-config/tasks/rgw_systemd_environment_file.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-config : create rados gateway instance directories] ***
 changed: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 changed: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-config : generate environment file] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 ## TASK [ceph-config : reset num_osds] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : create ceph conf directory] ***
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht4]
 changed: [cepht2]
 changed: [cepht5]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 changed: [cepht3]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht1]
 changed: [cepht5]
 ## TASK [ceph-mon : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mon : include deploy_monitors.yml] ***
 included: /ceph-ansible/roles/ceph-mon/tasks/deploy_monitors.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-mon : check if monitor initial keyring already exists] ***
 skipping: [cepht1]
 ## TASK [ceph-mon : generate monitor initial keyring] ***
 changed: [cepht1 -> localhost]
 ## TASK [ceph-mon : set_fact _initial_mon_key_success] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-mon : get initial keyring when it already exists] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-mon : create monitor initial keyring] ***
 changed: [cepht1]
 changed: [cepht4]
 changed: [cepht3]
 changed: [cepht2]
 changed: [cepht5]
 ## TASK [ceph-mon : copy the initial key in /etc/ceph (for containers)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mon : create monitor directory] ***
 changed: [cepht1]
 changed: [cepht5]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht3]
 ## TASK [ceph-mon : recursively fix ownership of monitor directory] ***
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht2]
 ## TASK [ceph-mon : create custom admin keyring] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mon : set_fact ceph-authtool container command] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-mon : import admin keyring into mon keyring] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [set_fact ceph-mon container command] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-mon : ceph monitor mkfs with keyring] ***
 changed: [cepht1]
 changed: [cepht2]
 changed: [cepht5]
 changed: [cepht3]
 changed: [cepht4]
 ## TASK [ceph-mon : ceph monitor mkfs without keyring] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mon : include start_monitor.yml] ***
 included: /ceph-ansible/roles/ceph-mon/tasks/start_monitor.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-mon : ensure systemd service override directory exists] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [add ceph-mon systemd service overrides] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mon : include_tasks systemd.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mon : start the monitor service] ***
 changed: [cepht1]
 changed: [cepht3]
 changed: [cepht2]
 changed: [cepht5]
 changed: [cepht4]
 ## TASK [ceph-mon : include_tasks ceph_keys.yml] ***
 included: /ceph-ansible/roles/ceph-mon/tasks/ceph_keys.yml for cepht1, cepht2, cepht4, cepht3, cepht5
 ## TASK [ceph-mon : waiting for the monitor(s) to form the quorum...] ***
 ok: [cepht1]
 ## TASK [ceph-mon : fetch ceph initial keys] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht5]
 ## TASK [ceph-mon : include secure_cluster.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : set_fact container_exec_cmd] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-mgr : include common.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : include pre_requisite.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : include start_mgr.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : include mgr_modules.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 RUNNING HANDLER [ceph-handler : mons handler] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/handler_mons.yml for cepht3, cepht2, cepht4, cepht1, cepht5
 RUNNING HANDLER [ceph-handler : set _mon_handler_called before restart] ***
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 RUNNING HANDLER [ceph-handler : copy mon restart script] ***
 changed: [cepht3]
 changed: [cepht5]
 changed: [cepht2]
 changed: [cepht1]
 changed: [cepht4]
 RUNNING HANDLER [ceph-handler : restart ceph mon daemon(s)] ***
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 RUNNING HANDLER [ceph-handler : set _mon_handler_called after restart] ***
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht1]
 RUNNING HANDLER [ceph-handler : osds handler] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/handler_osds.yml for cepht3, cepht2, cepht4, cepht1, cepht5
 RUNNING HANDLER [ceph-handler : set_fact trigger_restart] ***
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 RUNNING HANDLER [ceph-handler : set _osd_handler_called before restart] ***
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht1]
 RUNNING HANDLER [ceph-handler : unset noup flag] ***
 skipping: [cepht3]
 RUNNING HANDLER [ceph-handler : copy osd restart script] ***
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht1]
 RUNNING HANDLER [ceph-handler : get pool list] ***
 skipping: [cepht3]
 RUNNING HANDLER [ceph-handler : get balancer module status] ***
 skipping: [cepht3]
 RUNNING HANDLER [ceph-handler : set_fact pools_pgautoscaler_mode] ***
 RUNNING HANDLER [ceph-handler : disable balancer] ***
 skipping: [cepht3]
 RUNNING HANDLER [ceph-handler : disable pg autoscale on pools] ***
 skipping: [cepht3] => (item=None) 
 RUNNING HANDLER [ceph-handler : restart ceph osds daemon(s)] ***
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 RUNNING HANDLER [ceph-handler : set _osd_handler_called after restart] ***
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht1]
 RUNNING HANDLER [ceph-handler : re-enable pg autoscale on pools] ***
 skipping: [cepht3] => (item=None) 
 RUNNING HANDLER [ceph-handler : re-enable balancer] ***
 skipping: [cepht3]
 RUNNING HANDLER [ceph-handler : mdss handler] ***
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht2]
 skipping: [cepht1]
 skipping: [cepht5]
 RUNNING HANDLER [ceph-handler : rgws handler] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/handler_rgws.yml for cepht3, cepht2, cepht4, cepht1, cepht5
 RUNNING HANDLER [ceph-handler : set _rgw_handler_called before restart] ***
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht5]
 RUNNING HANDLER [ceph-handler : copy rgw restart script] ***
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht4]
 changed: [cepht5]
 changed: [cepht2]
 RUNNING HANDLER [ceph-handler : restart ceph rgw daemon(s)] ***
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 RUNNING HANDLER [ceph-handler : set _rgw_handler_called after restart] ***
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht5]
 RUNNING HANDLER [ceph-handler : rbdmirrors handler] ***
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht1]
 skipping: [cepht5]
 RUNNING HANDLER [ceph-handler : mgrs handler] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/handler_mgrs.yml for cepht3, cepht2, cepht4, cepht1, cepht5
 RUNNING HANDLER [ceph-handler : set _mgr_handler_called before restart] ***
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 RUNNING HANDLER [ceph-handler : copy mgr restart script] ***
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht5]
 changed: [cepht4]
 changed: [cepht2]
 RUNNING HANDLER [ceph-handler : restart ceph mgr daemon(s)] ***
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 RUNNING HANDLER [ceph-handler : set _mgr_handler_called after restart] ***
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht1]
 RUNNING HANDLER [ceph-handler : rbd-target-api and rbd-target-gw handler] ***
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 skipping: [cepht1]
 ## TASK [set ceph monitor install 'Complete'] ***
 ok: [cepht1]
 # PLAY [mgrs] ***
 ## TASK [set ceph manager install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 ok: [cepht1 -> cepht1] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.180826', 'end': '2022-01-18 17:13:32.187948', 'delta': '0:00:00.007122', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht2] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.395309', 'end': '2022-01-18 17:13:32.402194', 'delta': '0:00:00.006885', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht3] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.611378', 'end': '2022-01-18 17:13:32.618989', 'delta': '0:00:00.007611', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht4] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.840120', 'end': '2022-01-18 17:13:32.847495', 'delta': '0:00:00.007375', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht5] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:33.066909', 'end': '2022-01-18 17:13:33.073966', 'delta': '0:00:00.007057', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:33.358875', 'end': '2022-01-18 17:13:33.363342', 'delta': '0:00:00.004467', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.180826', 'end': '2022-01-18 17:13:32.187948', 'delta': '0:00:00.007122', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:33.587831', 'end': '2022-01-18 17:13:33.592411', 'delta': '0:00:00.004580', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.395309', 'end': '2022-01-18 17:13:32.402194', 'delta': '0:00:00.006885', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:33.803992', 'end': '2022-01-18 17:13:33.808674', 'delta': '0:00:00.004682', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.611378', 'end': '2022-01-18 17:13:32.618989', 'delta': '0:00:00.007611', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:34.028165', 'end': '2022-01-18 17:13:34.032670', 'delta': '0:00:00.004505', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:32.840120', 'end': '2022-01-18 17:13:32.847495', 'delta': '0:00:00.007375', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:34.262029', 'end': '2022-01-18 17:13:34.267516', 'delta': '0:00:00.005487', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:33.066909', 'end': '2022-01-18 17:13:33.073966', 'delta': '0:00:00.007057', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht5]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 ok: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final devices list] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht2]
 ok: [cepht4]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-handler : include check_running_containers.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : include check_socket_non_container.yml] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/check_socket_non_container.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-handler : find ceph mon socket] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph mon socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mon socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:39.743327', 'end': '2022-01-18 17:13:39.748682', 'delta': '0:00:00.005355', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:39.755059', 'end': '2022-01-18 17:13:39.757623', 'delta': '0:00:00.002564', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:39.746743', 'end': '2022-01-18 17:13:39.751158', 'delta': '0:00:00.004415', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:39.755801', 'end': '2022-01-18 17:13:39.760324', 'delta': '0:00:00.004523', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:13:39.765031', 'end': '2022-01-18 17:13:39.769533', 'delta': '0:00:00.004502', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph osd socket] ***
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph osd socket is in-use] ***
 ## TASK [ceph-handler : remove ceph osd socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph osd socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph mds socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-handler : remove ceph mds socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : find ceph rgw socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht3]
 ## TASK [ceph-handler : check if the ceph rgw socket is in-use] ***
 ## TASK [ceph-handler : remove ceph rgw socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph mgr socket] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph mgr socket is in-use] ***
 ## TASK [ceph-handler : remove ceph mgr socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph rbd mirror socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph rbd mirror socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph rbd mirror socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a nfs ganesha pid] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-handler : check for a tcmu-runner] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-api] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-gw] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a ceph-crash process] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht1]
 ok: [cepht4]
 ## TASK [ceph-handler : set_fact handler_mon_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_osd_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mds_status] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rgw_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_nfs_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rbd_status] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mgr_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_crash_status] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : reset num_osds] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : create rgw keyrings] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht1] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht3] => (item=None) 
 ## TASK [ceph-rgw : include_tasks multisite] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact multisite_called_from_handler_role] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 included: /ceph-ansible/roles/ceph-config/tasks/rgw_systemd_environment_file.yml for cepht1, cepht2, cepht3, cepht5, cepht4
 ## TASK [ceph-config : create rados gateway instance directories] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-config : generate environment file] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 ## TASK [ceph-config : reset num_osds] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-mgr : set_fact container_exec_cmd] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-mgr : include common.yml] ***
 included: /ceph-ansible/roles/ceph-mgr/tasks/common.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-mgr : create mgr directory] ***
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht5]
 ## TASK [ceph-mgr : fetch ceph mgr keyring] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-mgr : create ceph mgr keyring(s) on a mon node] ***
 changed: [cepht1 -> cepht1] => (item=None)
 changed: [cepht1 -> cepht1] => (item=None)
 changed: [cepht1 -> cepht1] => (item=None)
 changed: [cepht1 -> cepht1] => (item=None)
 changed: [cepht1 -> cepht1] => (item=None)
 changed: [cepht1 -> {{ groups[mon_group_name][0] }}]
 ## TASK [ceph-mgr : set_fact _mgr_keys] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-mgr : get keys from monitors] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht5] => (item=None) 
 changed: [cepht3 -> cepht5] => (item=None)
 changed: [cepht2 -> cepht5] => (item=None)
 changed: [cepht4 -> cepht5] => (item=None)
 changed: [cepht1 -> cepht5] => (item=None)
 changed: [cepht5 -> cepht5] => (item=None)
 ## TASK [ceph-mgr : copy ceph key(s) if needed] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht4] => (item=None) 
 changed: [cepht1] => (item=None)
 changed: [cepht3] => (item=None)
 changed: [cepht2] => (item=None)
 changed: [cepht5] => (item=None)
 changed: [cepht4] => (item=None)
 ## TASK [ceph-mgr : set mgr key permissions] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-mgr : append dashboard modules to ceph_mgr_modules] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-mgr : include pre_requisite.yml] ***
 included: /ceph-ansible/roles/ceph-mgr/tasks/pre_requisite.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-mgr : set_fact ceph_mgr_packages for sso] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-mgr : set_fact ceph_mgr_packages for dashboard] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-mgr : set_fact ceph_mgr_packages for non el7 distribution] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [install ceph-mgr packages on RedHat or SUSE] ***
 changed: [cepht3]
 changed: [cepht5]
 changed: [cepht4]
 changed: [cepht2]
 changed: [cepht1]
 ## TASK [install ceph-mgr packages for debian] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : include start_mgr.yml] ***
 included: /ceph-ansible/roles/ceph-mgr/tasks/start_mgr.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-mgr : ensure systemd service override directory exists] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [add ceph-mgr systemd service overrides] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : include_tasks systemd.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [enable ceph-mgr.target] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-mgr : systemd start mgr] ***
 changed: [cepht2]
 changed: [cepht3]
 changed: [cepht1]
 changed: [cepht5]
 changed: [cepht4]
 ## TASK [ceph-mgr : include mgr_modules.yml] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 included: /ceph-ansible/roles/ceph-mgr/tasks/mgr_modules.yml for cepht5
 ## TASK [ceph-mgr : wait for all mgr to be up] ***
 ok: [cepht5 -> cepht1]
 ## TASK [get enabled modules from ceph-mgr] ***
 ok: [cepht5 -> cepht1]
 ## TASK [ceph-mgr : set _ceph_mgr_modules fact (convert _ceph_mgr_modules.stdout to a dict)] ***
 ok: [cepht5]
 ## TASK [ceph-mgr : set _disabled_ceph_mgr_modules fact] ***
 ok: [cepht5]
 ## TASK [ceph-mgr : disable ceph mgr enabled modules] ***
 changed: [cepht5 -> cepht1] => (item=iostat)
 skipping: [cepht5] => (item=prometheus) 
 changed: [cepht5 -> cepht1] => (item=restful)
 ## TASK [add modules to ceph-mgr] ***
 changed: [cepht5 -> cepht1] => (item=dashboard)
 skipping: [cepht5] => (item=prometheus) 
 ## TASK [set ceph manager install 'Complete'] ***
 ok: [cepht1]
 # PLAY [osds] ***
 ## TASK [set ceph osd install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 ok: [cepht1 -> cepht1] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.244745', 'end': '2022-01-18 17:14:12.251295', 'delta': '0:00:00.006550', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht2] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.478334', 'end': '2022-01-18 17:14:12.485933', 'delta': '0:00:00.007599', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht3] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.702980', 'end': '2022-01-18 17:14:12.710363', 'delta': '0:00:00.007383', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht4] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.926703', 'end': '2022-01-18 17:14:12.934131', 'delta': '0:00:00.007428', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht5] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:13.151897', 'end': '2022-01-18 17:14:13.158400', 'delta': '0:00:00.006503', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:13.444407', 'end': '2022-01-18 17:14:13.447725', 'delta': '0:00:00.003318', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.244745', 'end': '2022-01-18 17:14:12.251295', 'delta': '0:00:00.006550', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:13.695044', 'end': '2022-01-18 17:14:13.700055', 'delta': '0:00:00.005011', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.478334', 'end': '2022-01-18 17:14:12.485933', 'delta': '0:00:00.007599', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:13.924707', 'end': '2022-01-18 17:14:13.930017', 'delta': '0:00:00.005310', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.702980', 'end': '2022-01-18 17:14:12.710363', 'delta': '0:00:00.007383', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:14.166952', 'end': '2022-01-18 17:14:14.171643', 'delta': '0:00:00.004691', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:12.926703', 'end': '2022-01-18 17:14:12.934131', 'delta': '0:00:00.007428', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:14.393832', 'end': '2022-01-18 17:14:14.398950', 'delta': '0:00:00.005118', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:13.151897', 'end': '2022-01-18 17:14:13.158400', 'delta': '0:00:00.006503', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht5]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 ok: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht5]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 skipping: [cepht4] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-handler : include check_running_containers.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : include check_socket_non_container.yml] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/check_socket_non_container.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-handler : find ceph mon socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph mon socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mon socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:20.431935', 'end': '2022-01-18 17:14:20.436253', 'delta': '0:00:00.004318', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:20.443452', 'end': '2022-01-18 17:14:20.447984', 'delta': '0:00:00.004532', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:20.451077', 'end': '2022-01-18 17:14:20.455531', 'delta': '0:00:00.004454', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:20.474691', 'end': '2022-01-18 17:14:20.479421', 'delta': '0:00:00.004730', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:20.483757', 'end': '2022-01-18 17:14:20.488216', 'delta': '0:00:00.004459', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph osd socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph osd socket is in-use] ***
 ## TASK [ceph-handler : remove ceph osd socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph osd socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph mds socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph mds socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : find ceph rgw socket] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-handler : check if the ceph rgw socket is in-use] ***
 ## TASK [ceph-handler : remove ceph rgw socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph mgr socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph mgr socket is in-use] ***
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 67291, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6899915, 'mtime': 1642497250.6899915, 'ctime': 1642497250.6899915, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 71104, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6468036, 'mtime': 1642497250.6468036, 'ctime': 1642497250.6468036, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 68905, 'dev': 24, 'nlink': 1, 'atime': 1642497250.571959, 'mtime': 1642497250.571959, 'ctime': 1642497250.571959, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 69816, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6903863, 'mtime': 1642497250.6903863, 'ctime': 1642497250.6903863, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 70899, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6626306, 'mtime': 1642497250.6626306, 'ctime': 1642497250.6626306, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mgr socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 71104, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6468036, 'mtime': 1642497250.6468036, 'ctime': 1642497250.6468036, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:22.158510', 'end': '2022-01-18 17:14:22.163350', 'delta': '0:00:00.004840', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 71104, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6468036, 'mtime': 1642497250.6468036, 'ctime': 1642497250.6468036, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 67291, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6899915, 'mtime': 1642497250.6899915, 'ctime': 1642497250.6899915, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:22.162401', 'end': '2022-01-18 17:14:22.164929', 'delta': '0:00:00.002528', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 67291, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6899915, 'mtime': 1642497250.6899915, 'ctime': 1642497250.6899915, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 68905, 'dev': 24, 'nlink': 1, 'atime': 1642497250.571959, 'mtime': 1642497250.571959, 'ctime': 1642497250.571959, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:22.179179', 'end': '2022-01-18 17:14:22.183575', 'delta': '0:00:00.004396', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 68905, 'dev': 24, 'nlink': 1, 'atime': 1642497250.571959, 'mtime': 1642497250.571959, 'ctime': 1642497250.571959, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 69816, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6903863, 'mtime': 1642497250.6903863, 'ctime': 1642497250.6903863, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:22.191438', 'end': '2022-01-18 17:14:22.196475', 'delta': '0:00:00.005037', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 69816, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6903863, 'mtime': 1642497250.6903863, 'ctime': 1642497250.6903863, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 70899, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6626306, 'mtime': 1642497250.6626306, 'ctime': 1642497250.6626306, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:14:22.195024', 'end': '2022-01-18 17:14:22.199523', 'delta': '0:00:00.004499', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 70899, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6626306, 'mtime': 1642497250.6626306, 'ctime': 1642497250.6626306, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph rbd mirror socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph rbd mirror socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph rbd mirror socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a nfs ganesha pid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a tcmu-runner] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-api] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-gw] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a ceph-crash process] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mon_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_osd_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mds_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rgw_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_nfs_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rbd_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mgr_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_crash_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : reset num_osds] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : create rgw keyrings] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht1] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht5] => (item=None) 
 ## TASK [ceph-rgw : include_tasks multisite] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact multisite_called_from_handler_role] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 included: /ceph-ansible/roles/ceph-config/tasks/rgw_systemd_environment_file.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-config : create rados gateway instance directories] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-config : generate environment file] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 ## TASK [ceph-config : reset num_osds] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht5]
 ## TASK [ceph-osd : set_fact add_osd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-osd : set_fact container_exec_cmd] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-osd : include_tasks system_tuning.yml] ***
 included: /ceph-ansible/roles/ceph-osd/tasks/system_tuning.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-osd : disable osd directory parsing by updatedb] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : disable osd directory path in updatedb.conf] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : create tmpfiles.d directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : disable transparent hugepage] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : get default vm.min_free_kbytes] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-osd : set_fact vm_min_free_kbytes] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-osd : apply operating system tuning] ***
 changed: [cepht1] => (item={'name': 'fs.aio-max-nr', 'value': '1048576', 'enable': True})
 changed: [cepht3] => (item={'name': 'fs.aio-max-nr', 'value': '1048576', 'enable': True})
 changed: [cepht4] => (item={'name': 'fs.aio-max-nr', 'value': '1048576', 'enable': True})
 changed: [cepht5] => (item={'name': 'fs.aio-max-nr', 'value': '1048576', 'enable': True})
 changed: [cepht2] => (item={'name': 'fs.aio-max-nr', 'value': '1048576', 'enable': True})
 changed: [cepht3] => (item={'name': 'fs.file-max', 'value': 26234859})
 changed: [cepht5] => (item={'name': 'fs.file-max', 'value': 26234859})
 changed: [cepht4] => (item={'name': 'fs.file-max', 'value': 26234859})
 changed: [cepht1] => (item={'name': 'fs.file-max', 'value': 26234859})
 changed: [cepht2] => (item={'name': 'fs.file-max', 'value': 26234859})
 changed: [cepht3] => (item={'name': 'vm.zone_reclaim_mode', 'value': 0})
 changed: [cepht5] => (item={'name': 'vm.zone_reclaim_mode', 'value': 0})
 changed: [cepht1] => (item={'name': 'vm.zone_reclaim_mode', 'value': 0})
 changed: [cepht2] => (item={'name': 'vm.zone_reclaim_mode', 'value': 0})
 changed: [cepht4] => (item={'name': 'vm.zone_reclaim_mode', 'value': 0})
 changed: [cepht3] => (item={'name': 'vm.swappiness', 'value': 10})
 changed: [cepht5] => (item={'name': 'vm.swappiness', 'value': 10})
 changed: [cepht4] => (item={'name': 'vm.swappiness', 'value': 10})
 changed: [cepht2] => (item={'name': 'vm.swappiness', 'value': 10})
 changed: [cepht1] => (item={'name': 'vm.swappiness', 'value': 10})
 changed: [cepht5] => (item={'name': 'vm.min_free_kbytes', 'value': '67584'})
 changed: [cepht2] => (item={'name': 'vm.min_free_kbytes', 'value': '67584'})
 changed: [cepht1] => (item={'name': 'vm.min_free_kbytes', 'value': '67584'})
 changed: [cepht3] => (item={'name': 'vm.min_free_kbytes', 'value': '67584'})
 changed: [cepht4] => (item={'name': 'vm.min_free_kbytes', 'value': '67584'})
 ## TASK [ceph-osd : install dependencies] ***
 ok: [cepht5]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ## TASK [ceph-osd : install numactl when needed] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : include_tasks common.yml] ***
 included: /ceph-ansible/roles/ceph-osd/tasks/common.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-osd : create bootstrap-osd and osd directories] ***
 changed: [cepht3] => (item=/var/lib/ceph/bootstrap-osd/)
 changed: [cepht1] => (item=/var/lib/ceph/bootstrap-osd/)
 changed: [cepht4] => (item=/var/lib/ceph/bootstrap-osd/)
 changed: [cepht5] => (item=/var/lib/ceph/bootstrap-osd/)
 changed: [cepht2] => (item=/var/lib/ceph/bootstrap-osd/)
 changed: [cepht3] => (item=/var/lib/ceph/osd/)
 changed: [cepht1] => (item=/var/lib/ceph/osd/)
 changed: [cepht5] => (item=/var/lib/ceph/osd/)
 changed: [cepht4] => (item=/var/lib/ceph/osd/)
 changed: [cepht2] => (item=/var/lib/ceph/osd/)
 ## TASK [ceph-osd : get keys from monitors] ***
 changed: [cepht1 -> cepht1] => (item=None)
 skipping: [cepht1] => (item=None) 
 changed: [cepht1 -> {{ groups.get(mon_group_name)[0] }}]
 ## TASK [ceph-osd : copy ceph key(s) if needed] ***
 changed: [cepht2] => (item=None)
 skipping: [cepht2] => (item=None) 
 changed: [cepht2]
 changed: [cepht1] => (item=None)
 skipping: [cepht1] => (item=None) 
 changed: [cepht1]
 changed: [cepht3] => (item=None)
 skipping: [cepht3] => (item=None) 
 changed: [cepht3]
 changed: [cepht4] => (item=None)
 changed: [cepht5] => (item=None)
 skipping: [cepht4] => (item=None) 
 changed: [cepht4]
 skipping: [cepht5] => (item=None) 
 changed: [cepht5]
 ## TASK [ceph-osd : set noup flag] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-osd : include container_options_facts.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : include_tasks scenarios/lvm.yml] ***
 included: /ceph-ansible/roles/ceph-osd/tasks/scenarios/lvm.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-osd : use ceph-volume to create bluestore osds] ***
 changed: [cepht3] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 changed: [cepht5] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 changed: [cepht1] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 changed: [cepht2] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 changed: [cepht4] => (item={'data': '/dev/sdb', 'crush_device_class': 'ssd'})
 changed: [cepht3] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 changed: [cepht2] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 changed: [cepht4] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 changed: [cepht5] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 changed: [cepht1] => (item={'data': '/dev/sdd', 'crush_device_class': 'hdd'})
 ## TASK [ceph-osd : include_tasks scenarios/lvm-batch.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : include_tasks start_osds.yml] ***
 included: /ceph-ansible/roles/ceph-osd/tasks/start_osds.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-osd : umount ceph disk (if on openstack)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : get osd ids] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-osd : set_fact container_exec_start_osd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-osd : collect osd ids] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-osd : include_tasks systemd.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : ensure systemd service override directory exists] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [add ceph-osd systemd service overrides] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : ensure "/var/lib/ceph/osd/{{ cluster }}-{{ item }}" is present] ***
 changed: [cepht2] => (item=1)
 changed: [cepht1] => (item=4)
 changed: [cepht5] => (item=2)
 changed: [cepht3] => (item=0)
 changed: [cepht4] => (item=3)
 changed: [cepht2] => (item=7)
 changed: [cepht5] => (item=5)
 changed: [cepht3] => (item=6)
 changed: [cepht4] => (item=9)
 changed: [cepht1] => (item=8)
 ## TASK [ceph-osd : systemd start osd] ***
 ok: [cepht2] => (item=1)
 ok: [cepht3] => (item=0)
 ok: [cepht1] => (item=4)
 ok: [cepht4] => (item=3)
 ok: [cepht5] => (item=2)
 ok: [cepht3] => (item=6)
 ok: [cepht2] => (item=7)
 ok: [cepht1] => (item=8)
 ok: [cepht5] => (item=5)
 ok: [cepht4] => (item=9)
 ## TASK [ceph-osd : unset noup flag] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 changed: [cepht5 -> cepht1]
 ## TASK [ceph-osd : wait for all osd to be up] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 ok: [cepht5 -> cepht1]
 ## TASK [ceph-osd : include crush_rules.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-osd : include openstack_config.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [set ceph osd install 'Complete'] ***
 ok: [cepht1]
 # PLAY [mdss] ***
 skipping: no hosts matched
 # PLAY [rgws] ***
 ## TASK [set ceph rgw install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht2]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 ok: [cepht1 -> cepht1] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:04.720437', 'end': '2022-01-18 17:15:04.727663', 'delta': '0:00:00.007226', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht2] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:04.949779', 'end': '2022-01-18 17:15:04.957289', 'delta': '0:00:00.007510', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht3] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.175710', 'end': '2022-01-18 17:15:05.183190', 'delta': '0:00:00.007480', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht4] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.395864', 'end': '2022-01-18 17:15:05.403290', 'delta': '0:00:00.007426', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht5] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.628927', 'end': '2022-01-18 17:15:05.636266', 'delta': '0:00:00.007339', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.929834', 'end': '2022-01-18 17:15:05.935487', 'delta': '0:00:00.005653', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:04.720437', 'end': '2022-01-18 17:15:04.727663', 'delta': '0:00:00.007226', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:06.166556', 'end': '2022-01-18 17:15:06.171235', 'delta': '0:00:00.004679', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:04.949779', 'end': '2022-01-18 17:15:04.957289', 'delta': '0:00:00.007510', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:06.391028', 'end': '2022-01-18 17:15:06.393456', 'delta': '0:00:00.002428', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.175710', 'end': '2022-01-18 17:15:05.183190', 'delta': '0:00:00.007480', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:06.614853', 'end': '2022-01-18 17:15:06.620160', 'delta': '0:00:00.005307', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.395864', 'end': '2022-01-18 17:15:05.403290', 'delta': '0:00:00.007426', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:06.840354', 'end': '2022-01-18 17:15:06.845056', 'delta': '0:00:00.004702', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:05.628927', 'end': '2022-01-18 17:15:05.636266', 'delta': '0:00:00.007339', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht5]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 ok: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht2]
 ok: [cepht4]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-handler : include check_running_containers.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : include check_socket_non_container.yml] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/check_socket_non_container.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-handler : find ceph mon socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph mon socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mon socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:12.382257', 'end': '2022-01-18 17:15:12.386758', 'delta': '0:00:00.004501', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:12.394731', 'end': '2022-01-18 17:15:12.399307', 'delta': '0:00:00.004576', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:12.404663', 'end': '2022-01-18 17:15:12.409155', 'delta': '0:00:00.004492', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:12.415851', 'end': '2022-01-18 17:15:12.420275', 'delta': '0:00:00.004424', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:12.416987', 'end': '2022-01-18 17:15:12.421509', 'delta': '0:00:00.004522', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph osd socket] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht2]
 ## TASK [ceph-handler : check if the ceph osd socket is in-use] ***
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-osd.6.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77428, 'dev': 24, 'nlink': 1, 'atime': 1642497287.581725, 'mtime': 1642497287.581725, 'ctime': 1642497287.581725, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-osd.9.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76638, 'dev': 24, 'nlink': 1, 'atime': 1642497287.7541418, 'mtime': 1642497287.7541418, 'ctime': 1642497287.7541418, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-osd.7.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75539, 'dev': 24, 'nlink': 1, 'atime': 1642497287.6827712, 'mtime': 1642497287.6827712, 'ctime': 1642497287.6827712, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-osd.5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77656, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8364058, 'mtime': 1642497287.8364058, 'ctime': 1642497287.8364058, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-osd.8.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 78430, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8705664, 'mtime': 1642497287.8705664, 'ctime': 1642497287.8705664, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-osd.0.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76824, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8237567, 'mtime': 1642497282.8237567, 'ctime': 1642497282.8237567, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-osd.1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 72582, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8658001, 'mtime': 1642497282.8658001, 'ctime': 1642497282.8658001, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-osd.2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75341, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8434365, 'mtime': 1642497282.8434365, 'ctime': 1642497282.8434365, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-osd.3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 73665, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8711743, 'mtime': 1642497282.8711743, 'ctime': 1642497282.8711743, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-osd.4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75670, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8545995, 'mtime': 1642497282.8545995, 'ctime': 1642497282.8545995, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph osd socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-osd.8.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 78430, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8705664, 'mtime': 1642497287.8705664, 'ctime': 1642497287.8705664, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.8.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.043734', 'end': '2022-01-18 17:15:13.048246', 'delta': '0:00:00.004512', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.8.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.8.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 78430, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8705664, 'mtime': 1642497287.8705664, 'ctime': 1642497287.8705664, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-osd.7.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75539, 'dev': 24, 'nlink': 1, 'atime': 1642497287.6827712, 'mtime': 1642497287.6827712, 'ctime': 1642497287.6827712, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.7.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.040799', 'end': '2022-01-18 17:15:13.045356', 'delta': '0:00:00.004557', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.7.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.7.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75539, 'dev': 24, 'nlink': 1, 'atime': 1642497287.6827712, 'mtime': 1642497287.6827712, 'ctime': 1642497287.6827712, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-osd.1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 72582, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8658001, 'mtime': 1642497282.8658001, 'ctime': 1642497282.8658001, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.261188', 'end': '2022-01-18 17:15:13.265670', 'delta': '0:00:00.004482', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 72582, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8658001, 'mtime': 1642497282.8658001, 'ctime': 1642497282.8658001, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-osd.4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75670, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8545995, 'mtime': 1642497282.8545995, 'ctime': 1642497282.8545995, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.289223', 'end': '2022-01-18 17:15:13.292015', 'delta': '0:00:00.002792', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75670, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8545995, 'mtime': 1642497282.8545995, 'ctime': 1642497282.8545995, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-osd.6.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77428, 'dev': 24, 'nlink': 1, 'atime': 1642497287.581725, 'mtime': 1642497287.581725, 'ctime': 1642497287.581725, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.6.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.038308', 'end': '2022-01-18 17:15:13.042574', 'delta': '0:00:00.004266', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.6.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.6.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77428, 'dev': 24, 'nlink': 1, 'atime': 1642497287.581725, 'mtime': 1642497287.581725, 'ctime': 1642497287.581725, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-osd.0.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76824, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8237567, 'mtime': 1642497282.8237567, 'ctime': 1642497282.8237567, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.0.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.258208', 'end': '2022-01-18 17:15:13.262599', 'delta': '0:00:00.004391', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.0.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.0.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76824, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8237567, 'mtime': 1642497282.8237567, 'ctime': 1642497282.8237567, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-osd.5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77656, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8364058, 'mtime': 1642497287.8364058, 'ctime': 1642497287.8364058, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.048907', 'end': '2022-01-18 17:15:13.053299', 'delta': '0:00:00.004392', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77656, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8364058, 'mtime': 1642497287.8364058, 'ctime': 1642497287.8364058, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-osd.9.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76638, 'dev': 24, 'nlink': 1, 'atime': 1642497287.7541418, 'mtime': 1642497287.7541418, 'ctime': 1642497287.7541418, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.9.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.037390', 'end': '2022-01-18 17:15:13.042050', 'delta': '0:00:00.004660', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.9.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.9.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76638, 'dev': 24, 'nlink': 1, 'atime': 1642497287.7541418, 'mtime': 1642497287.7541418, 'ctime': 1642497287.7541418, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-osd.2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75341, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8434365, 'mtime': 1642497282.8434365, 'ctime': 1642497282.8434365, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.262609', 'end': '2022-01-18 17:15:13.267023', 'delta': '0:00:00.004414', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75341, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8434365, 'mtime': 1642497282.8434365, 'ctime': 1642497282.8434365, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-osd.3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 73665, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8711743, 'mtime': 1642497282.8711743, 'ctime': 1642497282.8711743, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:13.272869', 'end': '2022-01-18 17:15:13.277405', 'delta': '0:00:00.004536', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 73665, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8711743, 'mtime': 1642497282.8711743, 'ctime': 1642497282.8711743, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph osd socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph mds socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph mds socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : find ceph rgw socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-handler : check if the ceph rgw socket is in-use] ***
 ## TASK [ceph-handler : remove ceph rgw socket if exists and not used by a process] ***
 ## TASK [ceph-handler : find ceph mgr socket] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph mgr socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 71104, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6468036, 'mtime': 1642497250.6468036, 'ctime': 1642497250.6468036, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 67291, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6899915, 'mtime': 1642497250.6899915, 'ctime': 1642497250.6899915, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 68905, 'dev': 24, 'nlink': 1, 'atime': 1642497250.571959, 'mtime': 1642497250.571959, 'ctime': 1642497250.571959, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 69816, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6903863, 'mtime': 1642497250.6903863, 'ctime': 1642497250.6903863, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 70899, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6626306, 'mtime': 1642497250.6626306, 'ctime': 1642497250.6626306, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mgr socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 71104, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6468036, 'mtime': 1642497250.6468036, 'ctime': 1642497250.6468036, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:14.517897', 'end': '2022-01-18 17:15:14.521843', 'delta': '0:00:00.003946', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 71104, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6468036, 'mtime': 1642497250.6468036, 'ctime': 1642497250.6468036, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 67291, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6899915, 'mtime': 1642497250.6899915, 'ctime': 1642497250.6899915, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:14.532101', 'end': '2022-01-18 17:15:14.536974', 'delta': '0:00:00.004873', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 67291, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6899915, 'mtime': 1642497250.6899915, 'ctime': 1642497250.6899915, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 68905, 'dev': 24, 'nlink': 1, 'atime': 1642497250.571959, 'mtime': 1642497250.571959, 'ctime': 1642497250.571959, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:14.528990', 'end': '2022-01-18 17:15:14.534180', 'delta': '0:00:00.005190', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 68905, 'dev': 24, 'nlink': 1, 'atime': 1642497250.571959, 'mtime': 1642497250.571959, 'ctime': 1642497250.571959, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 69816, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6903863, 'mtime': 1642497250.6903863, 'ctime': 1642497250.6903863, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:14.535427', 'end': '2022-01-18 17:15:14.539957', 'delta': '0:00:00.004530', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 69816, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6903863, 'mtime': 1642497250.6903863, 'ctime': 1642497250.6903863, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 70899, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6626306, 'mtime': 1642497250.6626306, 'ctime': 1642497250.6626306, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:15:14.543454', 'end': '2022-01-18 17:15:14.547832', 'delta': '0:00:00.004378', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 70899, 'dev': 24, 'nlink': 1, 'atime': 1642497250.6626306, 'mtime': 1642497250.6626306, 'ctime': 1642497250.6626306, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph rbd mirror socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph rbd mirror socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph rbd mirror socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a nfs ganesha pid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a tcmu-runner] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-api] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-gw] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a ceph-crash process] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mon_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_osd_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mds_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rgw_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_nfs_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rbd_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mgr_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_crash_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 skipping: [cepht3]
 ## TASK [ceph-config : reset num_osds] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : create rgw keyrings] ***
 skipping: [cepht1] => (item=None) 
 skipping: [cepht1] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht2] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht4] => (item=None) 
 skipping: [cepht3] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht5] => (item=None) 
 skipping: [cepht3] => (item=None) 
 ## TASK [ceph-rgw : include_tasks multisite] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact multisite_called_from_handler_role] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 included: /ceph-ansible/roles/ceph-config/tasks/rgw_systemd_environment_file.yml for cepht1, cepht3, cepht2, cepht4, cepht5
 ## TASK [ceph-config : create rados gateway instance directories] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-config : generate environment file] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 ## TASK [ceph-config : reset num_osds] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-rgw : include common.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/common.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-rgw : create rados gateway directories] ***
 changed: [cepht3] => (item=/var/run/ceph)
 changed: [cepht2] => (item=/var/run/ceph)
 changed: [cepht1] => (item=/var/run/ceph)
 changed: [cepht5] => (item=/var/run/ceph)
 changed: [cepht4] => (item=/var/run/ceph)
 ## TASK [ceph-rgw : get keys from monitors] ***
 changed: [cepht1 -> cepht1] => (item=None)
 skipping: [cepht1] => (item=None) 
 changed: [cepht1 -> {{ groups.get(mon_group_name)[0] }}]
 ## TASK [ceph-rgw : copy ceph key(s) if needed] ***
 changed: [cepht1] => (item=None)
 skipping: [cepht1] => (item=None) 
 changed: [cepht3] => (item=None)
 skipping: [cepht3] => (item=None) 
 changed: [cepht1]
 changed: [cepht3]
 changed: [cepht2] => (item=None)
 skipping: [cepht2] => (item=None) 
 changed: [cepht2]
 changed: [cepht5] => (item=None)
 skipping: [cepht5] => (item=None) 
 changed: [cepht5]
 changed: [cepht4] => (item=None)
 skipping: [cepht4] => (item=None) 
 changed: [cepht4]
 ## TASK [ceph-rgw : copy SSL certificate & key data to certificate path] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : include_tasks pre_requisite.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/pre_requisite.yml for cepht1, cepht3, cepht2, cepht4, cepht5
 ## TASK [ceph-rgw : create rgw keyrings] ***
 changed: [cepht2] => (item=None)
 changed: [cepht1] => (item=None)
 changed: [cepht3] => (item=None)
 changed: [cepht4] => (item=None)
 changed: [cepht5] => (item=None)
 changed: [cepht2] => (item=None)
 changed: [cepht3] => (item=None)
 changed: [cepht4] => (item=None)
 changed: [cepht4]
 changed: [cepht1] => (item=None)
 changed: [cepht5] => (item=None)
 changed: [cepht5]
 changed: [cepht1]
 changed: [cepht3] => (item=None)
 changed: [cepht3]
 changed: [cepht2] => (item=None)
 changed: [cepht2]
 ## TASK [ceph-rgw : rgw pool creation tasks] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/rgw_create_pools.yml for cepht1
 ## TASK [ceph-rgw : create ec profile] ***
 changed: [cepht1 -> cepht1] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}})
 ## TASK [ceph-rgw : create ec crush rule] ***
 changed: [cepht1 -> cepht1] => (item={'key': 'hdd-ec', 'value': {'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'ec_k': 2, 'ec_m': 1, 'crush_device_class': 'hdd', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'ec_plugin': 'isa', 'ec_technique': 'cauchy'}})
 ## TASK [ceph-rgw : create ec pools for rgw] ***
 skipping: [cepht1] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}})
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 skipping: [cepht1] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}}) 
 [WARNING]: The value False (type bool) in a string field was converted to 'False' (type string). If this does not look like what you expect, quote the entire value to ensure it does not change.

 ## TASK [ceph-rgw : create replicated crush rule] ***
 changed: [cepht1 -> cepht1] => (item={'key': 'ssd-rep-rule', 'value': {'rule_name': 'ssd-rep-rule', 'crush_root': 'default', 'crush_failure_domain': 'osd', 'crush_device_class': 'ssd'}})
 ## TASK [ceph-rgw : create replicated pools for rgw] ***
 changed: [cepht1 -> cepht1] => (item={'key': '.rgw.root', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 skipping: [cepht1] => (item={'key': 'yh-z1.rgw.buckets.data', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'ec', 'ec_profile': 'hdd-ec', 'rule_name': 'hdd-ec-rule', 'pg_autoscale_mode': False}}) 
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.buckets.non-ec', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.otp', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'yh-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'es-z1.rgw.buckets.index', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'es-z1.rgw.meta', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'es-z1.rgw.log', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 changed: [cepht1 -> cepht1] => (item={'key': 'es-z1.rgw.control', 'value': {'pg_num': 32, 'pgp_num': 32, 'type': 'replicated', 'size': 3, 'rule_name': 'ssd-rep-rule', 'pg_autoscale_mode': False}})
 ## TASK [ceph-rgw : include_tasks openstack-keystone.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-rgw : include_tasks start_radosgw.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : include start_docker_rgw.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : include_tasks yh_es_sync/main.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/yh_es_sync/main.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-rgw : set_fact realms] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 skipping: [cepht1] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1', 'host': 'cepht3'}) 
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ## TASK [ceph-rgw : create list zonegroups] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ## TASK [ceph-rgw : create list zones] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ## TASK [ceph-rgw : create master zone endpoints list] ***
 ok: [cepht1] => (item=cepht4)
 ## TASK [ceph-rgw : create elasticsearch zone endpoints list] ***
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-rgw : create a list of zones and all their endpoints] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ## TASK [ceph-rgw : include_tasks multisite/master.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/multisite/master.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-rgw : create the realm(s)] ***
 changed: [cepht1 -> cepht1] => (item=yh-realm)
 ## TASK [ceph-rgw : create zonegroup(s)] ***
 changed: [cepht1 -> cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'is_master': True})
 ## TASK [ceph-rgw : create the master zone(s)] ***
 changed: [cepht1 -> cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'yh-z1', 'is_master': 'True', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'})
 skipping: [cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'es-z1', 'is_master': 'False', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 changed: [cepht1 -> cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'yh-z1', 'is_master': 'True', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'})
 ## TASK [ceph-rgw : add endpoints to their zone groups(s)] ***
 skipping: [cepht1] => (item={'zone': 'yh-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'True', 'endpoints': 'http://cepht4:8064', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 skipping: [cepht1] => (item={'zone': 'es-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'False', 'endpoints': 'http://cepht5:8062', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 ## TASK [ceph-rgw : add endpoints to their zone(s)] ***
 changed: [cepht1 -> cepht1] => (item={'zone': 'yh-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'True', 'endpoints': 'http://cepht4:8064', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'})
 skipping: [cepht1] => (item={'zone': 'es-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'False', 'endpoints': 'http://cepht5:8062', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 ## TASK [ceph-rgw : update period for zone creation] ***
 skipping: [cepht1] => (item={'zone': 'yh-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'True', 'endpoints': 'http://cepht4:8064', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 skipping: [cepht1] => (item={'zone': 'es-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'False', 'endpoints': 'http://cepht5:8062', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 ## TASK [ceph-rgw : include_tasks create_zone_user.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/multisite/create_zone_user.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-rgw : create list zone_users] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'})
 skipping: [cepht1] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1', 'host': 'cepht3'}) 
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'})
 ## TASK [ceph-rgw : create the zone user(s)] ***
 changed: [cepht1 -> cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'yh-z1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'user': 'es-sync', 'display_name': 'Elastic Sync User'})
 ## TASK [ceph-rgw : include_tasks multisite/secondary.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/multisite/secondary.yml for cepht1, cepht2, cepht4, cepht3, cepht5
 ## TASK [ceph-rgw : create list secondary_realms] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht1'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht2'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht3'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1', 'host': 'cepht3'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht4'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'host': 'cepht5'}) 
 ## TASK [ceph-rgw : ensure connection to primary cluster from mon] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-rgw : ensure connection to primary cluster from rgw] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 ## TASK [ceph-rgw : fetch the realm(s)] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-rgw : get the period(s)] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-rgw : create the zone(s)] ***
 skipping: [cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'yh-z1', 'is_master': 'True', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 changed: [cepht1 -> cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'es-z1', 'is_master': 'False', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 skipping: [cepht1] => (item={'realm': 'yh-realm', 'zonegroup': 'yh-zg1', 'zone': 'yh-z1', 'is_master': 'True', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 ## TASK [ceph-rgw : add endpoints to their zone(s)] ***
 skipping: [cepht1] => (item={'zone': 'yh-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'True', 'endpoints': 'http://cepht4:8064', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 changed: [cepht1 -> cepht1] => (item={'zone': 'es-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'False', 'endpoints': 'http://cepht5:8062', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'})
 ## TASK [ceph-rgw : update period for zone creation] ***
 skipping: [cepht1] => (item={'zone': 'yh-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'True', 'endpoints': 'http://cepht4:8064', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 skipping: [cepht1] => (item={'zone': 'es-z1', 'zonegroup': 'yh-zg1', 'realm': 'yh-realm', 'is_master': 'False', 'endpoints': 'http://cepht5:8062', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB'}) 
 ## TASK [ceph-rgw : include_tasks start_radosgw.yml] ***
 included: /ceph-ansible/roles/ceph-rgw/tasks/start_radosgw.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-rgw : ensure systemd service override directory exists] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [add ceph-rgw systemd service overrides] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : start rgw instance] ***
 changed: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 changed: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-rgw : enable the ceph-radosgw.target service] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-rgw : include_tasks start_docker_rgw.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-rgw : include_tasks multisite/main.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [set ceph rgw install 'Complete'] ***
 ok: [cepht1]
 # PLAY [clients] ***
 skipping: no hosts matched
 # PLAY [nfss] ***
 skipping: no hosts matched
 # PLAY [rbdmirrors] ***
 skipping: no hosts matched
 # PLAY [iscsigws,iscsi-gws] ***
 skipping: no hosts matched
 # PLAY [rgwloadbalancers] ***
 skipping: no hosts matched
 # PLAY [mons,osds,mdss,rgws,mgrs,rbdmirrors,nfss,iscsigws,grafana-server] ***
 ## TASK [set ceph node exporter install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht4, cepht3, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht3]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 ok: [cepht1 -> cepht1] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:19.661864', 'end': '2022-01-18 17:16:19.667563', 'delta': '0:00:00.005699', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht2] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:19.905856', 'end': '2022-01-18 17:16:19.913426', 'delta': '0:00:00.007570', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht3] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:20.184323', 'end': '2022-01-18 17:16:20.192612', 'delta': '0:00:00.008289', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht4] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:20.430433', 'end': '2022-01-18 17:16:20.437933', 'delta': '0:00:00.007500', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht5] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:20.709797', 'end': '2022-01-18 17:16:20.714135', 'delta': '0:00:00.004338', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:21.043897', 'end': '2022-01-18 17:16:21.049552', 'delta': '0:00:00.005655', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:19.661864', 'end': '2022-01-18 17:16:19.667563', 'delta': '0:00:00.005699', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:21.298558', 'end': '2022-01-18 17:16:21.303676', 'delta': '0:00:00.005118', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:19.905856', 'end': '2022-01-18 17:16:19.913426', 'delta': '0:00:00.007570', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:21.575111', 'end': '2022-01-18 17:16:21.581410', 'delta': '0:00:00.006299', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:20.184323', 'end': '2022-01-18 17:16:20.192612', 'delta': '0:00:00.008289', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:21.843098', 'end': '2022-01-18 17:16:21.848381', 'delta': '0:00:00.005283', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:20.430433', 'end': '2022-01-18 17:16:20.437933', 'delta': '0:00:00.007500', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:22.107874', 'end': '2022-01-18 17:16:22.113612', 'delta': '0:00:00.005738', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:20.709797', 'end': '2022-01-18 17:16:20.714135', 'delta': '0:00:00.004338', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht5]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht1]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 ok: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht2] => (item=0) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht1] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht3] => (item=0) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht1] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-container-engine : include pre_requisites/prerequisites.yml] ***
 included: /ceph-ansible/roles/ceph-container-engine/tasks/pre_requisites/prerequisites.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-container-engine : include specific variables] ***
 ok: [cepht1] => (item=/ceph-ansible/roles/ceph-container-engine/vars/CentOS-8.yml)
 ok: [cepht2] => (item=/ceph-ansible/roles/ceph-container-engine/vars/CentOS-8.yml)
 ok: [cepht3] => (item=/ceph-ansible/roles/ceph-container-engine/vars/CentOS-8.yml)
 ok: [cepht4] => (item=/ceph-ansible/roles/ceph-container-engine/vars/CentOS-8.yml)
 ok: [cepht5] => (item=/ceph-ansible/roles/ceph-container-engine/vars/CentOS-8.yml)
 ## TASK [ceph-container-engine : debian based systems tasks] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-container-engine : enable extras on centos] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-container-engine : install container packages] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-container-engine : install lvm2 package] ***
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht4]
 ## TASK [ceph-container-engine : create the systemd docker override directory] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-container-engine : create the systemd docker override file] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-container-engine : remove docker proxy configuration] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-container-engine : restart docker] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-container-engine : start container service] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-container-common : container registry authentication] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-node-exporter : include setup_container.yml] ***
 included: /ceph-ansible/roles/ceph-node-exporter/tasks/setup_container.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-node-exporter : include_tasks systemd.yml] ***
 included: /ceph-ansible/roles/ceph-node-exporter/tasks/systemd.yml for cepht2, cepht1, cepht3, cepht4, cepht5
 ## TASK [ceph-node-exporter : ship systemd service] ***
 changed: [cepht1]
 changed: [cepht5]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht3]
 ## TASK [ceph-node-exporter : start the node_exporter service] ***
 changed: [cepht3]
 changed: [cepht5]
 changed: [cepht2]
 changed: [cepht4]
 changed: [cepht1]
 ## TASK [set ceph node exporter install 'Complete'] ***
 ok: [cepht1]
 # PLAY [grafana-server] ***
 ## TASK [set ceph grafana install 'In Progress'] ***
 ok: [cepht4]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht4
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht4]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht4 -> cepht1] => (item=cepht1)
 ok: [cepht4 -> cepht2] => (item=cepht2)
 ok: [cepht4 -> cepht3] => (item=cepht3)
 ok: [cepht4 -> cepht4] => (item=cepht4)
 ok: [cepht4 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht4 -> cepht1] => (item=cepht1)
 ok: [cepht4 -> cepht2] => (item=cepht2)
 ok: [cepht4 -> cepht3] => (item=cepht3)
 ok: [cepht4 -> cepht4] => (item=cepht4)
 ok: [cepht4 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 ok: [cepht4 -> cepht1] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:39.701095', 'end': '2022-01-18 17:16:39.706766', 'delta': '0:00:00.005671', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'})
 ok: [cepht4 -> cepht2] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:39.966330', 'end': '2022-01-18 17:16:39.973889', 'delta': '0:00:00.007559', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'})
 ok: [cepht4 -> cepht3] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:40.233897', 'end': '2022-01-18 17:16:40.241297', 'delta': '0:00:00.007400', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'})
 ok: [cepht4 -> cepht4] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:40.479213', 'end': '2022-01-18 17:16:40.486446', 'delta': '0:00:00.007233', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'})
 ok: [cepht4 -> cepht5] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:40.736825', 'end': '2022-01-18 17:16:40.744307', 'delta': '0:00:00.007482', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 ok: [cepht4] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:41.071160', 'end': '2022-01-18 17:16:41.076240', 'delta': '0:00:00.005080', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:39.701095', 'end': '2022-01-18 17:16:39.706766', 'delta': '0:00:00.005671', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht4] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:41.342402', 'end': '2022-01-18 17:16:41.346267', 'delta': '0:00:00.003865', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:39.966330', 'end': '2022-01-18 17:16:39.973889', 'delta': '0:00:00.007559', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht4] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:41.614860', 'end': '2022-01-18 17:16:41.620258', 'delta': '0:00:00.005398', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:40.233897', 'end': '2022-01-18 17:16:40.241297', 'delta': '0:00:00.007400', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht4] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:41.887377', 'end': '2022-01-18 17:16:41.892674', 'delta': '0:00:00.005297', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:40.479213', 'end': '2022-01-18 17:16:40.486446', 'delta': '0:00:00.007233', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht4] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:42.157717', 'end': '2022-01-18 17:16:42.162127', 'delta': '0:00:00.004410', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:16:40.736825', 'end': '2022-01-18 17:16:40.744307', 'delta': '0:00:00.007482', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht4] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht4 -> cepht5]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 ok: [cepht4]
 ## TASK [ceph-facts : generate cluster fsid] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : resolve device link(s)] ***
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final devices list] ***
 ok: [cepht4]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 ok: [cepht4]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht4]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 ok: [cepht4]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht4] => (item=0) 
 skipping: [cepht4] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht4] => (item=cepht1)
 ok: [cepht4] => (item=cepht2)
 ok: [cepht4] => (item=cepht3)
 ok: [cepht4] => (item=cepht4)
 ok: [cepht4] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht4 -> cepht1] => (item=cepht1)
 ok: [cepht4 -> cepht2] => (item=cepht2)
 ok: [cepht4 -> cepht3] => (item=cepht3)
 ok: [cepht4 -> cepht4] => (item=cepht4)
 ok: [cepht4 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht4 -> cepht1] => (item=cepht1)
 ok: [cepht4 -> cepht2] => (item=cepht2)
 ok: [cepht4 -> cepht3] => (item=cepht3)
 ok: [cepht4 -> cepht4] => (item=cepht4)
 ok: [cepht4 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set grafana_server_addr fact - ipv4] ***
 ok: [cepht4]
 ## TASK [ceph-facts : set grafana_server_addr fact - ipv6] ***
 skipping: [cepht4]
 ## TASK [ceph-facts : set grafana_server_addrs fact - ipv4] ***
 ok: [cepht4] => (item=cepht4)
 ## TASK [ceph-facts : set grafana_server_addrs fact - ipv6] ***
 skipping: [cepht4] => (item=cepht4) 
 ## TASK [ceph-prometheus : create prometheus directories] ***
 changed: [cepht4] => (item=/etc/prometheus)
 changed: [cepht4] => (item=/var/lib/prometheus)
 ## TASK [ceph-prometheus : write prometheus config file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 changed: [cepht4]
 ## TASK [ceph-prometheus : make sure the alerting rules directory exists] ***
 changed: [cepht4]
 ## TASK [ceph-prometheus : copy alerting rules] ***
 changed: [cepht4]
 ## TASK [ceph-prometheus : create alertmanager directories] ***
 changed: [cepht4] => (item=/etc/alertmanager)
 changed: [cepht4] => (item=/var/lib/alertmanager)
 ## TASK [ceph-prometheus : write alertmanager config file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 changed: [cepht4]
 ## TASK [ceph-prometheus : include setup_container.yml] ***
 included: /ceph-ansible/roles/ceph-prometheus/tasks/setup_container.yml for cepht4
 ## TASK [ceph-prometheus : include_tasks systemd.yml] ***
 included: /ceph-ansible/roles/ceph-prometheus/tasks/systemd.yml for cepht4
 ## TASK [ceph-prometheus : ship systemd services] ***
 changed: [cepht4] => (item=alertmanager.service)
 changed: [cepht4] => (item=prometheus.service)
 ## TASK [ceph-prometheus : start prometheus services] ***
 changed: [cepht4] => (item=prometheus)
 changed: [cepht4] => (item=alertmanager)
 ## TASK [ceph-grafana : include setup_container.yml] ***
 included: /ceph-ansible/roles/ceph-grafana/tasks/setup_container.yml for cepht4
 ## TASK [ceph-grafana : create /etc/grafana and /var/lib/grafana] ***
 changed: [cepht4] => (item=/etc/grafana)
 changed: [cepht4] => (item=/var/lib/grafana)
 [WARNING]: The value 472 (type int) in a string field was converted to '472' (type string). If this does not look like what you expect, quote the entire value to ensure it does not change.

 ## TASK [ceph-grafana : include_tasks systemd.yml] ***
 included: /ceph-ansible/roles/ceph-grafana/tasks/systemd.yml for cepht4
 ## TASK [ceph-grafana : ship systemd service] ***
 changed: [cepht4]
 ## TASK [ceph-grafana : start the grafana-server service] ***
 changed: [cepht4]
 ## TASK [ceph-grafana : include configure_grafana.yml] ***
 included: /ceph-ansible/roles/ceph-grafana/tasks/configure_grafana.yml for cepht4
 ## TASK [install ceph-grafana-dashboards package on RedHat or SUSE] ***
 ok: [cepht4]
 ## TASK [ceph-grafana : make sure grafana is down] ***
 changed: [cepht4]
 ## TASK [ceph-grafana : wait for grafana to be stopped] ***
 ok: [cepht4]
 ## TASK [ceph-grafana : make sure grafana configuration directories exist] ***
 ok: [cepht4] => (item=/etc/grafana/dashboards/ceph-dashboard)
 changed: [cepht4] => (item=/etc/grafana/provisioning/datasources)
 changed: [cepht4] => (item=/etc/grafana/provisioning/dashboards)
 changed: [cepht4] => (item=/etc/grafana/provisioning/notifiers)
 ## TASK [ceph-grafana : download ceph grafana dashboards] ***
 skipping: [cepht4] => (item=ceph-cluster.json) 
 skipping: [cepht4] => (item=cephfs-overview.json) 
 skipping: [cepht4] => (item=host-details.json) 
 skipping: [cepht4] => (item=hosts-overview.json) 
 skipping: [cepht4] => (item=osd-device-details.json) 
 skipping: [cepht4] => (item=osds-overview.json) 
 skipping: [cepht4] => (item=pool-detail.json) 
 skipping: [cepht4] => (item=pool-overview.json) 
 skipping: [cepht4] => (item=radosgw-detail.json) 
 skipping: [cepht4] => (item=radosgw-overview.json) 
 skipping: [cepht4] => (item=radosgw-sync-overview.json) 
 skipping: [cepht4] => (item=rbd-details.json) 
 skipping: [cepht4] => (item=rbd-overview.json) 
 ## TASK [ceph-grafana : write grafana.ini] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 changed: [cepht4]
 ## TASK [ceph-grafana : write datasources provisioning config file] ***
 changed: [cepht4]
 ## TASK [ceph-grafana : Write dashboards provisioning config file] ***
 changed: [cepht4]
 ## TASK [ceph-grafana : copy grafana SSL certificate file] ***
 skipping: [cepht4]
 ## TASK [ceph-grafana : copy grafana SSL certificate key] ***
 skipping: [cepht4]
 ## TASK [ceph-grafana : generate a Self Signed OpenSSL certificate for dashboard] ***
 skipping: [cepht4]
 ## TASK [ceph-grafana : enable and start grafana] ***
 changed: [cepht4]
 ## TASK [ceph-grafana : wait for grafana to start] ***
 ok: [cepht4]
 RUNNING HANDLER [ceph-prometheus : service handler] ***
 changed: [cepht4] => (item=alertmanager)
 changed: [cepht4] => (item=prometheus)
 ## TASK [set ceph grafana install 'Complete'] ***
 ok: [cepht4]
 # PLAY [['cepht1', 'cepht2', 'cepht3', 'cepht4', 'cepht5']] ***
 ## TASK [set ceph dashboard install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : include facts.yml] ***
 included: /ceph-ansible/roles/ceph-facts/tasks/facts.yml for cepht1, cepht2, cepht4, cepht3, cepht5
 ## TASK [ceph-facts : check if it is atomic host] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact is_atomic] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact discovered_interpreter_python if not previously set] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_release ceph_stable_release] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact monitor_name ansible_facts['hostname']] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : find a running mon container] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 ## TASK [ceph-facts : check for a ceph mon socket] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : check if the ceph mon socket is in-use] ***
 ok: [cepht1 -> cepht1] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.144375', 'end': '2022-01-18 17:17:20.151417', 'delta': '0:00:00.007042', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht2] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.431500', 'end': '2022-01-18 17:17:20.434352', 'delta': '0:00:00.002852', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht3] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.684847', 'end': '2022-01-18 17:17:20.690711', 'delta': '0:00:00.005864', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht4] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.948094', 'end': '2022-01-18 17:17:20.954732', 'delta': '0:00:00.006638', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'})
 ok: [cepht1 -> cepht5] => (item={'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:21.206451', 'end': '2022-01-18 17:17:21.213450', 'delta': '0:00:00.006999', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - non_container] ***
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:21.533779', 'end': '2022-01-18 17:17:21.538187', 'delta': '0:00:00.004408', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht1.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.144375', 'end': '2022-01-18 17:17:20.151417', 'delta': '0:00:00.007042', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht1.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht1', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:21.796332', 'end': '2022-01-18 17:17:21.800767', 'delta': '0:00:00.004435', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht2.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.431500', 'end': '2022-01-18 17:17:20.434352', 'delta': '0:00:00.002852', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht2.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht2', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:22.066963', 'end': '2022-01-18 17:17:22.071466', 'delta': '0:00:00.004503', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht3.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.684847', 'end': '2022-01-18 17:17:20.690711', 'delta': '0:00:00.005864', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht3.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht3', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:22.320579', 'end': '2022-01-18 17:17:22.325748', 'delta': '0:00:00.005169', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht4.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:20.948094', 'end': '2022-01-18 17:17:20.954732', 'delta': '0:00:00.006638', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht4.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht4', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ok: [cepht1] => (item={'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:22.582144', 'end': '2022-01-18 17:17:22.586640', 'delta': '0:00:00.004496', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'cmd': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', 'stdout': '/var/run/ceph/ceph-mon.cepht5.asok', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:17:21.206451', 'end': '2022-01-18 17:17:21.213450', 'delta': '0:00:00.006999', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'stat --printf=%n /var/run/ceph/ceph-mon*.asok', '_uses_shell': True, 'warn': True, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': ['/var/run/ceph/ceph-mon.cepht5.asok'], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': 'cepht5', 'ansible_loop_var': 'item'}, 'ansible_loop_var': 'item'})
 ## TASK [ceph-facts : set_fact running_mon - container] ***
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht1', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht2', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht3', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht4', 'ansible_loop_var': 'item'}) 
 skipping: [cepht1] => (item={'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'cepht5', 'ansible_loop_var': 'item'}) 
 ## TASK [ceph-facts : set_fact _container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid if cluster is already running] ***
 ok: [cepht1 -> cepht5]
 ## TASK [ceph-facts : set_fact current_fsid rc 1] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : get current fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact fsid from current_fsid] ***
 ok: [cepht1]
 ## TASK [ceph-facts : generate cluster fsid] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact fsid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-facts : resolve device link(s)] ***
 ## TASK [ceph-facts : set_fact build devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final devices list] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve dedicated_device link(s)] ***
 ## TASK [ceph-facts : set_fact build dedicated_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final dedicated_devices list] ***
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : resolve bluestore_wal_device link(s)] ***
 ## TASK [ceph-facts : set_fact build bluestore_wal_devices from resolved symlinks] ***
 ## TASK [ceph-facts : set_fact build final bluestore_wal_devices list] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht3]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact devices generate device list when osd_auto_discovery] ***
 skipping: [cepht2] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdd', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht2] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht3] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdb', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht4] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sde', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '1073741824', 'sectorsize': '512', 'size': '512.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht1] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sdc', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {}, 'rotational': '0', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 skipping: [cepht5] => (item={'key': 'sda', 'value': {'virtual': 1, 'links': {'ids': [], 'uuids': [], 'labels': [], 'masters': []}, 'vendor': 'VMware', 'model': 'Virtual disk', 'sas_address': None, 'sas_device_handle': None, 'removable': '0', 'support_discard': '4096', 'partitions': {'sda2': {'links': {'ids': [], 'uuids': ['7f13a332-ee76-4084-8176-3799e796e18d'], 'labels': [], 'masters': []}, 'start': '1230848', 'sectors': '2097152', 'sectorsize': 512, 'size': '1.00 GB', 'uuid': '7f13a332-ee76-4084-8176-3799e796e18d', 'holders': []}, 'sda3': {'links': {'ids': [], 'uuids': ['b2ada45d-a864-4579-857c-79a0a899bd01'], 'labels': [], 'masters': []}, 'start': '3328000', 'sectors': '265105408', 'sectorsize': 512, 'size': '126.41 GB', 'uuid': 'b2ada45d-a864-4579-857c-79a0a899bd01', 'holders': []}, 'sda1': {'links': {'ids': [], 'uuids': ['B5D2-42CF'], 'labels': [], 'masters': []}, 'start': '2048', 'sectors': '1228800', 'sectorsize': 512, 'size': '600.00 MB', 'uuid': 'B5D2-42CF', 'holders': []}}, 'rotational': '1', 'scheduler_mode': 'mq-deadline', 'sectors': '268435456', 'sectorsize': '512', 'size': '128.00 GB', 'host': 'Serial Attached SCSI controller: VMware PVSCSI SCSI Controller (rev 02)', 'holders': []}}) 
 ## TASK [ceph-facts : get ceph current status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact ceph_current_status] ***
 skipping: [cepht1]
 ## TASK [ceph-facts : set_fact rgw_hostname] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : check if the ceph conf exists] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set default osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : read osd pool default crush rule] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set osd_pool_default_crush_rule fact] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv4] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address_block ipv6] ***
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_address] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv4] ***
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _monitor_addresses to monitor_interface - ipv6] ***
 skipping: [cepht1] => (item=cepht1) 
 skipping: [cepht2] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht1) 
 skipping: [cepht3] => (item=cepht1) 
 skipping: [cepht1] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht2) 
 skipping: [cepht2] => (item=cepht3) 
 skipping: [cepht4] => (item=cepht3) 
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht2) 
 skipping: [cepht5] => (item=cepht1) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht1] => (item=cepht5) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht5) 
 skipping: [cepht3] => (item=cepht3) 
 skipping: [cepht5] => (item=cepht2) 
 skipping: [cepht4] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht3) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht5) 
 skipping: [cepht5] => (item=cepht5) 
 ## TASK [ceph-facts : set_fact _current_monitor_address] ***
 ok: [cepht1] => (item={'name': 'cepht1', 'addr': '192.168.87.1'})
 skipping: [cepht2] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht4] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 ok: [cepht2] => (item={'name': 'cepht2', 'addr': '192.168.87.2'})
 skipping: [cepht4] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht3] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht2] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht4] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht5] => (item={'name': 'cepht1', 'addr': '192.168.87.1'}) 
 skipping: [cepht1] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht2] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 ok: [cepht4] => (item={'name': 'cepht4', 'addr': '192.168.87.4'})
 skipping: [cepht3] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht1] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht5] => (item={'name': 'cepht2', 'addr': '192.168.87.2'}) 
 skipping: [cepht2] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 skipping: [cepht4] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht3] => (item={'name': 'cepht3', 'addr': '192.168.87.3'})
 skipping: [cepht5] => (item={'name': 'cepht3', 'addr': '192.168.87.3'}) 
 skipping: [cepht3] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht5] => (item={'name': 'cepht4', 'addr': '192.168.87.4'}) 
 skipping: [cepht3] => (item={'name': 'cepht5', 'addr': '192.168.87.5'}) 
 ok: [cepht5] => (item={'name': 'cepht5', 'addr': '192.168.87.5'})
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address_block ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_address] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _interface] ***
 skipping: [cepht2]
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact _radosgw_address to radosgw_interface - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances without rgw multisite|rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact is_rgw_instances_defined] ***
 ok: [cepht2]
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw multisite] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_client_instances with rgw_yh_es_sync] ***
 skipping: [cepht1] => (item=0) 
 skipping: [cepht1] => (item=1) 
 skipping: [cepht3] => (item=0) 
 skipping: [cepht4] => (item=0) 
 skipping: [cepht3] => (item=1) 
 skipping: [cepht2] => (item=0) 
 skipping: [cepht5] => (item=0) 
 skipping: [cepht4] => (item=1) 
 skipping: [cepht2] => (item=1) 
 skipping: [cepht5] => (item=1) 
 ## TASK [ceph-facts : set_fact rgw_yh_master_instances] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_yh_esync_instances] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances with rgw_yh_es_sync] ***
 skipping: [cepht1]
 skipping: [cepht3]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact rgw_instances_host] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-facts : set_fact rgw_instances_all] ***
 ok: [cepht1] => (item=cepht1)
 ok: [cepht1] => (item=cepht2)
 ok: [cepht1] => (item=cepht3)
 ok: [cepht1] => (item=cepht4)
 ok: [cepht1] => (item=cepht5)
 ## TASK [ceph-facts : set_fact use_new_ceph_iscsi package or old ceph-iscsi-config/cli] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set_fact ceph_run_cmd] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set_fact ceph_admin_command] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht2] => (item=cepht2)
 ok: [cepht1 -> cepht3] => (item=cepht3)
 ok: [cepht1 -> cepht4] => (item=cepht4)
 ok: [cepht1 -> cepht5] => (item=cepht5)
 ## TASK [ceph-facts : set grafana_server_addr fact - ipv4] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 ok: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set grafana_server_addr fact - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-facts : set grafana_server_addrs fact - ipv4] ***
 ok: [cepht1] => (item=cepht4)
 ok: [cepht2] => (item=cepht4)
 ok: [cepht3] => (item=cepht4)
 ok: [cepht4] => (item=cepht4)
 ok: [cepht5] => (item=cepht4)
 ## TASK [ceph-facts : set grafana_server_addrs fact - ipv6] ***
 skipping: [cepht1] => (item=cepht4) 
 skipping: [cepht2] => (item=cepht4) 
 skipping: [cepht3] => (item=cepht4) 
 skipping: [cepht4] => (item=cepht4) 
 skipping: [cepht5] => (item=cepht4) 
 ## TASK [ceph-dashboard : include configure_dashboard.yml] ***
 included: /ceph-ansible/roles/ceph-dashboard/tasks/configure_dashboard.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-dashboard : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-dashboard : set_fact container_run_cmd] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-dashboard : get current mgr backend - ipv4] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-dashboard : get current mgr backend - ipv6] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-dashboard : get SSL status for dashboard] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : disable SSL for dashboard] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : enable SSL for dashboard] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : copy dashboard SSL certificate file] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-dashboard : copy dashboard SSL certificate key] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-dashboard : set_fact subj_alt_names] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : create tempfile for openssl certificate and key generation] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : copy the openssl configuration file] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : add subjectAltName to the openssl configuration] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : generate a Self Signed OpenSSL certificate for dashboard] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : remove the openssl tempfile] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : slurp self-signed generated certificate for dashboard] ***
 skipping: [cepht1] => (item=ceph-dashboard.key) 
 skipping: [cepht1] => (item=ceph-dashboard.crt) 
 ## TASK [ceph-dashboard : copy self-signed generated certificate on mons] ***
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.key', 'ansible_loop_var': 'item'}, 'cepht1']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.key', 'ansible_loop_var': 'item'}, 'cepht2']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.key', 'ansible_loop_var': 'item'}, 'cepht3']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.key', 'ansible_loop_var': 'item'}, 'cepht4']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.key', 'ansible_loop_var': 'item'}, 'cepht5']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.crt', 'ansible_loop_var': 'item'}, 'cepht1']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.crt', 'ansible_loop_var': 'item'}, 'cepht2']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.crt', 'ansible_loop_var': 'item'}, 'cepht3']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.crt', 'ansible_loop_var': 'item'}, 'cepht4']) 
 skipping: [cepht1] => (item=[{'changed': False, 'skipped': True, 'skip_reason': 'Conditional result was False', 'item': 'ceph-dashboard.crt', 'ansible_loop_var': 'item'}, 'cepht5']) 
 ## TASK [ceph-dashboard : import dashboard certificate file] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : import dashboard certificate key] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : set the dashboard port (8080)] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the dashboard SSL port (8080)] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : config the current dashboard backend] ***
 ok: [cepht1 -> cepht1] => (item=cepht1)
 ok: [cepht1 -> cepht1] => (item=cepht2)
 ok: [cepht1 -> cepht1] => (item=cepht3)
 ok: [cepht1 -> cepht1] => (item=cepht4)
 ok: [cepht1 -> cepht1] => (item=cepht5)
 ## TASK [ceph-dashboard : disable mgr dashboard module (restart)] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : enable mgr dashboard module (restart)] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : check dashboard password in file option command] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set_fact dashboard_password_from_stdin] ***
 ok: [cepht1]
 ## TASK [ceph-dashboard : create dashboard admin user] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : disable unused dashboard features] ***
 ## TASK [ceph-dashboard : set grafana api user] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set grafana api password] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set grafana api password (legacy)] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : disable ssl verification for grafana] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : set alertmanager host] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set prometheus host] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : include_tasks] ***
 included: /ceph-ansible/roles/ceph-dashboard/tasks/configure_grafana_layouts.yml for cepht2, cepht1, cepht3, cepht4, cepht5
 ## TASK [ceph-dashboard : set grafana url] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : inject grafana dashboard layouts] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : config grafana api url vip] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : config alertmanager api url] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : config prometheus api url] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : create radosgw system user] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : get the rgw access and secret keys] ***
 ok: [cepht1]
 ## TASK [ceph-dashboard : set the rgw user] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the rgw access key] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the rgw access key (legacy)] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : set the rgw secret key] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the rgw secret key (legacy)] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : set the rgw host] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the rgw port] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the rgw scheme] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : set the rgw admin resource] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : disable ssl verification for rgw] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : disable iscsi api ssl verification] ***
 skipping: [cepht1]
 ## TASK [ceph-dashboard : add iscsi gateways - ipv4] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-dashboard : add iscsi gateways - ipv4 (legacy)] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-dashboard : add iscsi gateways - ipv6] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-dashboard : add iscsi gateways - ipv6 (legacy)] ***
 skipping: [cepht1] => (item=None) 
 ## TASK [ceph-dashboard : disable mgr dashboard module (restart)] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : enable mgr dashboard module (restart)] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-dashboard : print dashboard URL] ***
 ok: [cepht1] => 
cess your dashboard web UI at http://cepht1:8080/ as an 'admin' user with 'vyRj59!#e6/RpTzy' password.
 ## TASK [set ceph dashboard install 'Complete'] ***
 ok: [cepht1]
 # PLAY [mons,osds,mdss,rgws,rbdmirrors,mgrs] ***
 ## TASK [set ceph crash install 'In Progress'] ***
 ok: [cepht1]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht1]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht2]
 ok: [cepht4]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-handler : include check_running_containers.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : include check_socket_non_container.yml] ***
 included: /ceph-ansible/roles/ceph-handler/tasks/check_socket_non_container.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-handler : find ceph mon socket] ***
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht1]
 ok: [cepht3]
 ## TASK [ceph-handler : check if the ceph mon socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mon socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.301456', 'end': '2022-01-18 17:18:05.304236', 'delta': '0:00:00.002780', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62852, 'dev': 24, 'nlink': 1, 'atime': 1642497204.0230875, 'mtime': 1642497183.2182155, 'ctime': 1642497183.2182155, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.322167', 'end': '2022-01-18 17:18:05.327236', 'delta': '0:00:00.005069', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62867, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2433834, 'mtime': 1642497183.2433834, 'ctime': 1642497183.2433834, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.343294', 'end': '2022-01-18 17:18:05.348128', 'delta': '0:00:00.004834', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 59106, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2113578, 'mtime': 1642497183.2113578, 'ctime': 1642497183.2113578, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.339928', 'end': '2022-01-18 17:18:05.342906', 'delta': '0:00:00.002978', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62171, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2598276, 'mtime': 1642497183.2598276, 'ctime': 1642497183.2598276, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mon.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.341861', 'end': '2022-01-18 17:18:05.346512', 'delta': '0:00:00.004651', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mon.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mon.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 62615, 'dev': 24, 'nlink': 1, 'atime': 1642497183.2430277, 'mtime': 1642497183.2430277, 'ctime': 1642497183.2430277, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph osd socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : check if the ceph osd socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-osd.8.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 78430, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8705664, 'mtime': 1642497287.8705664, 'ctime': 1642497287.8705664, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-osd.9.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76638, 'dev': 24, 'nlink': 1, 'atime': 1642497287.7541418, 'mtime': 1642497287.7541418, 'ctime': 1642497287.7541418, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-osd.6.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77428, 'dev': 24, 'nlink': 1, 'atime': 1642497287.581725, 'mtime': 1642497287.581725, 'ctime': 1642497287.581725, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-osd.5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77656, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8364058, 'mtime': 1642497287.8364058, 'ctime': 1642497287.8364058, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-osd.7.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75539, 'dev': 24, 'nlink': 1, 'atime': 1642497287.6827712, 'mtime': 1642497287.6827712, 'ctime': 1642497287.6827712, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-osd.3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 73665, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8711743, 'mtime': 1642497282.8711743, 'ctime': 1642497282.8711743, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-osd.0.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76824, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8237567, 'mtime': 1642497282.8237567, 'ctime': 1642497282.8237567, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-osd.4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75670, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8545995, 'mtime': 1642497282.8545995, 'ctime': 1642497282.8545995, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-osd.2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75341, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8434365, 'mtime': 1642497282.8434365, 'ctime': 1642497282.8434365, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-osd.1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 72582, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8658001, 'mtime': 1642497282.8658001, 'ctime': 1642497282.8658001, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph osd socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-osd.8.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 78430, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8705664, 'mtime': 1642497287.8705664, 'ctime': 1642497287.8705664, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.8.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.948903', 'end': '2022-01-18 17:18:05.953676', 'delta': '0:00:00.004773', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.8.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.8.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 78430, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8705664, 'mtime': 1642497287.8705664, 'ctime': 1642497287.8705664, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-osd.4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75670, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8545995, 'mtime': 1642497282.8545995, 'ctime': 1642497282.8545995, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:06.203744', 'end': '2022-01-18 17:18:06.208373', 'delta': '0:00:00.004629', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75670, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8545995, 'mtime': 1642497282.8545995, 'ctime': 1642497282.8545995, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-osd.7.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75539, 'dev': 24, 'nlink': 1, 'atime': 1642497287.6827712, 'mtime': 1642497287.6827712, 'ctime': 1642497287.6827712, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.7.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.972004', 'end': '2022-01-18 17:18:05.976803', 'delta': '0:00:00.004799', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.7.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.7.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75539, 'dev': 24, 'nlink': 1, 'atime': 1642497287.6827712, 'mtime': 1642497287.6827712, 'ctime': 1642497287.6827712, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-osd.1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 72582, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8658001, 'mtime': 1642497282.8658001, 'ctime': 1642497282.8658001, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:06.221451', 'end': '2022-01-18 17:18:06.224173', 'delta': '0:00:00.002722', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 72582, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8658001, 'mtime': 1642497282.8658001, 'ctime': 1642497282.8658001, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-osd.6.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77428, 'dev': 24, 'nlink': 1, 'atime': 1642497287.581725, 'mtime': 1642497287.581725, 'ctime': 1642497287.581725, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.6.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.973116', 'end': '2022-01-18 17:18:05.977687', 'delta': '0:00:00.004571', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.6.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.6.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77428, 'dev': 24, 'nlink': 1, 'atime': 1642497287.581725, 'mtime': 1642497287.581725, 'ctime': 1642497287.581725, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-osd.0.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76824, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8237567, 'mtime': 1642497282.8237567, 'ctime': 1642497282.8237567, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.0.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:06.185069', 'end': '2022-01-18 17:18:06.189707', 'delta': '0:00:00.004638', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.0.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.0.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76824, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8237567, 'mtime': 1642497282.8237567, 'ctime': 1642497282.8237567, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-osd.9.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76638, 'dev': 24, 'nlink': 1, 'atime': 1642497287.7541418, 'mtime': 1642497287.7541418, 'ctime': 1642497287.7541418, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.9.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.954882', 'end': '2022-01-18 17:18:05.959569', 'delta': '0:00:00.004687', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.9.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.9.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 76638, 'dev': 24, 'nlink': 1, 'atime': 1642497287.7541418, 'mtime': 1642497287.7541418, 'ctime': 1642497287.7541418, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-osd.3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 73665, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8711743, 'mtime': 1642497282.8711743, 'ctime': 1642497282.8711743, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:06.180506', 'end': '2022-01-18 17:18:06.184114', 'delta': '0:00:00.003608', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 73665, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8711743, 'mtime': 1642497282.8711743, 'ctime': 1642497282.8711743, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-osd.5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77656, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8364058, 'mtime': 1642497287.8364058, 'ctime': 1642497287.8364058, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:05.980094', 'end': '2022-01-18 17:18:05.984670', 'delta': '0:00:00.004576', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 77656, 'dev': 24, 'nlink': 1, 'atime': 1642497287.8364058, 'mtime': 1642497287.8364058, 'ctime': 1642497287.8364058, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-osd.2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75341, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8434365, 'mtime': 1642497282.8434365, 'ctime': 1642497282.8434365, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-osd.2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:06.200803', 'end': '2022-01-18 17:18:06.205929', 'delta': '0:00:00.005126', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-osd.2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-osd.2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 75341, 'dev': 24, 'nlink': 1, 'atime': 1642497282.8434365, 'mtime': 1642497282.8434365, 'ctime': 1642497282.8434365, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph osd socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph mds socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph mds socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : find ceph rgw socket] ***
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht5]
 ok: [cepht1]
 ok: [cepht3]
 ## TASK [ceph-handler : check if the ceph rgw socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht1.client-1.25376.94095149094072.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 90430, 'dev': 24, 'nlink': 1, 'atime': 1642497375.297984, 'mtime': 1642497375.297984, 'ctime': 1642497375.297984, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht5.client-1.21770.94533479625912.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84200, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2478771, 'mtime': 1642497375.2478771, 'ctime': 1642497375.2478771, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht2.master.21660.94095665689784.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 82855, 'dev': 24, 'nlink': 1, 'atime': 1642497375.7252247, 'mtime': 1642497375.7252247, 'ctime': 1642497375.7252247, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht4.client-1.21528.94165468230840.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84245, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2175589, 'mtime': 1642497375.2175589, 'ctime': 1642497375.2175589, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht3.es.21675.94372841379000.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81898, 'dev': 24, 'nlink': 1, 'atime': 1642497375.8181345, 'mtime': 1642497375.8181345, 'ctime': 1642497375.8181345, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht5.client-0.21668.94601595040952.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81899, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7388802, 'mtime': 1642497374.7388802, 'ctime': 1642497374.7388802, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht2.client-1.21558.94160018388152.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84284, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2282279, 'mtime': 1642497375.2282279, 'ctime': 1642497375.2282279, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht4.client-0.21426.94045330805944.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81896, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7015622, 'mtime': 1642497374.7015622, 'ctime': 1642497374.7015622, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht1.client-0.25274.93905411413176.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 89084, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7859871, 'mtime': 1642497374.7859871, 'ctime': 1642497374.7859871, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht3.client-1.21573.94895393117368.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83392, 'dev': 24, 'nlink': 1, 'atime': 1642497375.272138, 'mtime': 1642497375.272138, 'ctime': 1642497375.272138, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht2.client-0.21456.94695659091128.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83256, 'dev': 24, 'nlink': 1, 'atime': 1642497374.713231, 'mtime': 1642497374.713231, 'ctime': 1642497374.713231, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-client.rgw.cepht3.client-0.21471.94146635412664.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83258, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7471416, 'mtime': 1642497374.7471416, 'ctime': 1642497374.7471416, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph rgw socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht1.client-1.25376.94095149094072.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 90430, 'dev': 24, 'nlink': 1, 'atime': 1642497375.297984, 'mtime': 1642497375.297984, 'ctime': 1642497375.297984, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht1.client-1.25376.94095149094072.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.039369', 'end': '2022-01-18 17:18:07.046146', 'delta': '0:00:00.006777', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht1.client-1.25376.94095149094072.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht1.client-1.25376.94095149094072.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 90430, 'dev': 24, 'nlink': 1, 'atime': 1642497375.297984, 'mtime': 1642497375.297984, 'ctime': 1642497375.297984, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht1.client-0.25274.93905411413176.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 89084, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7859871, 'mtime': 1642497374.7859871, 'ctime': 1642497374.7859871, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht1.client-0.25274.93905411413176.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.300347', 'end': '2022-01-18 17:18:07.305812', 'delta': '0:00:00.005465', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht1.client-0.25274.93905411413176.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht1.client-0.25274.93905411413176.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 89084, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7859871, 'mtime': 1642497374.7859871, 'ctime': 1642497374.7859871, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht2.master.21660.94095665689784.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 82855, 'dev': 24, 'nlink': 1, 'atime': 1642497375.7252247, 'mtime': 1642497375.7252247, 'ctime': 1642497375.7252247, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht2.master.21660.94095665689784.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.058779', 'end': '2022-01-18 17:18:07.063826', 'delta': '0:00:00.005047', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht2.master.21660.94095665689784.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht2.master.21660.94095665689784.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 82855, 'dev': 24, 'nlink': 1, 'atime': 1642497375.7252247, 'mtime': 1642497375.7252247, 'ctime': 1642497375.7252247, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht2.client-1.21558.94160018388152.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84284, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2282279, 'mtime': 1642497375.2282279, 'ctime': 1642497375.2282279, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht2.client-1.21558.94160018388152.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.289162', 'end': '2022-01-18 17:18:07.292030', 'delta': '0:00:00.002868', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht2.client-1.21558.94160018388152.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht2.client-1.21558.94160018388152.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84284, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2282279, 'mtime': 1642497375.2282279, 'ctime': 1642497375.2282279, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht2.client-0.21456.94695659091128.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83256, 'dev': 24, 'nlink': 1, 'atime': 1642497374.713231, 'mtime': 1642497374.713231, 'ctime': 1642497374.713231, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht2.client-0.21456.94695659091128.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.506285', 'end': '2022-01-18 17:18:07.509484', 'delta': '0:00:00.003199', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht2.client-0.21456.94695659091128.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht2.client-0.21456.94695659091128.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83256, 'dev': 24, 'nlink': 1, 'atime': 1642497374.713231, 'mtime': 1642497374.713231, 'ctime': 1642497374.713231, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht3.es.21675.94372841379000.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81898, 'dev': 24, 'nlink': 1, 'atime': 1642497375.8181345, 'mtime': 1642497375.8181345, 'ctime': 1642497375.8181345, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht3.es.21675.94372841379000.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.068138', 'end': '2022-01-18 17:18:07.072724', 'delta': '0:00:00.004586', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht3.es.21675.94372841379000.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht3.es.21675.94372841379000.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81898, 'dev': 24, 'nlink': 1, 'atime': 1642497375.8181345, 'mtime': 1642497375.8181345, 'ctime': 1642497375.8181345, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht3.client-1.21573.94895393117368.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83392, 'dev': 24, 'nlink': 1, 'atime': 1642497375.272138, 'mtime': 1642497375.272138, 'ctime': 1642497375.272138, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht3.client-1.21573.94895393117368.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.332569', 'end': '2022-01-18 17:18:07.337534', 'delta': '0:00:00.004965', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht3.client-1.21573.94895393117368.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht3.client-1.21573.94895393117368.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83392, 'dev': 24, 'nlink': 1, 'atime': 1642497375.272138, 'mtime': 1642497375.272138, 'ctime': 1642497375.272138, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht4.client-1.21528.94165468230840.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84245, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2175589, 'mtime': 1642497375.2175589, 'ctime': 1642497375.2175589, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht4.client-1.21528.94165468230840.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.069353', 'end': '2022-01-18 17:18:07.074247', 'delta': '0:00:00.004894', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht4.client-1.21528.94165468230840.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht4.client-1.21528.94165468230840.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84245, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2175589, 'mtime': 1642497375.2175589, 'ctime': 1642497375.2175589, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht4.client-0.21426.94045330805944.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81896, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7015622, 'mtime': 1642497374.7015622, 'ctime': 1642497374.7015622, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht4.client-0.21426.94045330805944.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.300275', 'end': '2022-01-18 17:18:07.305502', 'delta': '0:00:00.005227', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht4.client-0.21426.94045330805944.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht4.client-0.21426.94045330805944.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81896, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7015622, 'mtime': 1642497374.7015622, 'ctime': 1642497374.7015622, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht3.client-0.21471.94146635412664.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83258, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7471416, 'mtime': 1642497374.7471416, 'ctime': 1642497374.7471416, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht3.client-0.21471.94146635412664.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.561035', 'end': '2022-01-18 17:18:07.565124', 'delta': '0:00:00.004089', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht3.client-0.21471.94146635412664.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht3.client-0.21471.94146635412664.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 83258, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7471416, 'mtime': 1642497374.7471416, 'ctime': 1642497374.7471416, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht5.client-1.21770.94533479625912.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84200, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2478771, 'mtime': 1642497375.2478771, 'ctime': 1642497375.2478771, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht5.client-1.21770.94533479625912.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.066346', 'end': '2022-01-18 17:18:07.071210', 'delta': '0:00:00.004864', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht5.client-1.21770.94533479625912.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht5.client-1.21770.94533479625912.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 84200, 'dev': 24, 'nlink': 1, 'atime': 1642497375.2478771, 'mtime': 1642497375.2478771, 'ctime': 1642497375.2478771, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-client.rgw.cepht5.client-0.21668.94601595040952.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81899, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7388802, 'mtime': 1642497374.7388802, 'ctime': 1642497374.7388802, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-client.rgw.cepht5.client-0.21668.94601595040952.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:07.276959', 'end': '2022-01-18 17:18:07.281759', 'delta': '0:00:00.004800', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-client.rgw.cepht5.client-0.21668.94601595040952.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-client.rgw.cepht5.client-0.21668.94601595040952.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 81899, 'dev': 24, 'nlink': 1, 'atime': 1642497374.7388802, 'mtime': 1642497374.7388802, 'ctime': 1642497374.7388802, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph mgr socket] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht5]
 ok: [cepht3]
 ok: [cepht4]
 ## TASK [ceph-handler : check if the ceph mgr socket is in-use] ***
 ok: [cepht1] => (item={'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 100489, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8132288, 'mtime': 1642497485.8132288, 'ctime': 1642497485.8132288, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht4] => (item={'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 100137, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8227983, 'mtime': 1642497485.8227983, 'ctime': 1642497485.8227983, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht3] => (item={'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 90637, 'dev': 24, 'nlink': 1, 'atime': 1642497485.920399, 'mtime': 1642497485.920399, 'ctime': 1642497485.920399, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht2] => (item={'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 87955, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8715692, 'mtime': 1642497485.8715692, 'ctime': 1642497485.8715692, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ok: [cepht5] => (item={'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 91056, 'dev': 24, 'nlink': 1, 'atime': 1642497485.756208, 'mtime': 1642497485.756208, 'ctime': 1642497485.756208, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False})
 ## TASK [ceph-handler : remove ceph mgr socket if exists and not used by a process] ***
 skipping: [cepht1] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 100489, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8132288, 'mtime': 1642497485.8132288, 'ctime': 1642497485.8132288, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht1.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:08.197473', 'end': '2022-01-18 17:18:08.203496', 'delta': '0:00:00.006023', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht1.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht1.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 100489, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8132288, 'mtime': 1642497485.8132288, 'ctime': 1642497485.8132288, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht2] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 87955, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8715692, 'mtime': 1642497485.8715692, 'ctime': 1642497485.8715692, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht2.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:08.217312', 'end': '2022-01-18 17:18:08.221932', 'delta': '0:00:00.004620', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht2.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht2.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 87955, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8715692, 'mtime': 1642497485.8715692, 'ctime': 1642497485.8715692, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht3] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 90637, 'dev': 24, 'nlink': 1, 'atime': 1642497485.920399, 'mtime': 1642497485.920399, 'ctime': 1642497485.920399, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht3.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:08.216163', 'end': '2022-01-18 17:18:08.220838', 'delta': '0:00:00.004675', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht3.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht3.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 90637, 'dev': 24, 'nlink': 1, 'atime': 1642497485.920399, 'mtime': 1642497485.920399, 'ctime': 1642497485.920399, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht4] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 100137, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8227983, 'mtime': 1642497485.8227983, 'ctime': 1642497485.8227983, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht4.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:08.208276', 'end': '2022-01-18 17:18:08.212933', 'delta': '0:00:00.004657', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht4.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht4.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 100137, 'dev': 24, 'nlink': 1, 'atime': 1642497485.8227983, 'mtime': 1642497485.8227983, 'ctime': 1642497485.8227983, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 skipping: [cepht5] => (item=[{'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 91056, 'dev': 24, 'nlink': 1, 'atime': 1642497485.756208, 'mtime': 1642497485.756208, 'ctime': 1642497485.756208, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, {'cmd': ['grep', '-q', '/var/run/ceph/ceph-mgr.cepht5.asok', '/proc/net/unix'], 'stdout': '', 'stderr': '', 'rc': 0, 'start': '2022-01-18 17:18:08.276223', 'end': '2022-01-18 17:18:08.278465', 'delta': '0:00:00.002242', 'changed': False, 'invocation': {'module_args': {'_raw_params': 'grep -q /var/run/ceph/ceph-mgr.cepht5.asok /proc/net/unix', 'warn': True, '_uses_shell': False, 'stdin_add_newline': True, 'strip_empty_ends': True, 'argv': None, 'chdir': None, 'executable': None, 'creates': None, 'removes': None, 'stdin': None}}, 'stdout_lines': [], 'stderr_lines': [], 'failed': False, 'failed_when_result': False, 'item': {'path': '/var/run/ceph/ceph-mgr.cepht5.asok', 'mode': '0755', 'isdir': False, 'ischr': False, 'isblk': False, 'isreg': False, 'isfifo': False, 'islnk': False, 'issock': True, 'uid': 167, 'gid': 167, 'size': 0, 'inode': 91056, 'dev': 24, 'nlink': 1, 'atime': 1642497485.756208, 'mtime': 1642497485.756208, 'ctime': 1642497485.756208, 'gr_name': 'ceph', 'pw_name': 'ceph', 'wusr': True, 'rusr': True, 'xusr': True, 'wgrp': False, 'rgrp': True, 'xgrp': True, 'woth': False, 'roth': True, 'xoth': True, 'isuid': False, 'isgid': False}, 'ansible_loop_var': 'item'}]) 
 ## TASK [ceph-handler : find ceph rbd mirror socket] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check if the ceph rbd mirror socket is in-use] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : remove ceph rbd mirror socket if exists and not used by a process] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht5]
 skipping: [cepht4]
 ## TASK [ceph-handler : check for a nfs ganesha pid] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a tcmu-runner] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-api] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a rbd-target-gw] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : check for a ceph-crash process] ***
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht1]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mon_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_osd_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mds_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rgw_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-handler : set_fact handler_nfs_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_rbd_status] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact handler_mgr_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ## TASK [ceph-handler : set_fact handler_crash_status] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : include create_ceph_initial_dirs.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : include_tasks rgw_systemd_environment_file.yml] ***
 included: /ceph-ansible/roles/ceph-config/tasks/rgw_systemd_environment_file.yml for cepht1, cepht2, cepht3, cepht4, cepht5
 ## TASK [ceph-config : create rados gateway instance directories] ***
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'})
 ok: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'})
 ## TASK [ceph-config : generate environment file] ***
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht1] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.1', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht2] => (item={'rgw_yh_type': 'master', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'master', 'radosgw_address': '192.168.87.2', 'radosgw_frontend_port': 59200, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-0', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59100, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht5] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.5', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht4] => (item={'rgw_yh_type': 'client', 'rgw_zonemaster': 'True', 'rgw_zone': 'yh-z1', 'instance_name': 'client-1', 'radosgw_address': '192.168.87.4', 'radosgw_frontend_port': 59101, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User'}) 
 skipping: [cepht3] => (item={'rgw_yh_type': 'esync', 'rgw_zonemaster': 'False', 'rgw_zone': 'es-z1', 'instance_name': 'es', 'radosgw_address': '192.168.87.3', 'radosgw_frontend_port': 59300, 'rgw_realm': 'yh-realm', 'rgw_zonegroup': 'yh-zg1', 'system_access_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'system_secret_key': 'DC3751519DEEBDE8164700E95AF1CCFB', 'rgw_zone_user': 'es-sync', 'rgw_zone_user_display_name': 'Elastic Sync User', 'tier_type': 'elasticsearch', 'es_tier_conf_endpoint': 'http://192.168.0.110:9200', 'es_tier_conf_num_shards': 10, 'es_tier_conf_num_replicas': 1, 'es_tier_conf_explicit_custom_meta': False, 'es_tier_conf_override_index_path': 'cepht_1'}) 
 ## TASK [ceph-config : reset num_osds] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : count number of osds for lvm scenario] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-config : look up for ceph-volume rejected devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht4]
 skipping: [cepht3]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact rejected_devices] ***
 ## TASK [ceph-config : set_fact _devices] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm batch --report' to see how many osds are to be created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (legacy report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds from the output of 'ceph-volume lvm batch --report' (new report)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : run 'ceph-volume lvm list' to see how many osds have already been created] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : set_fact num_osds (add existing osds)] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-config : create ceph conf directory] ***
 ok: [cepht3]
 ok: [cepht5]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht2]
 ## TASK [ceph-config : generate ceph.conf configuration file] ***
 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 [DEPRECATION WARNING]: set_available_variables is being deprecated. Use "@available_variables.setter" instead.. This feature will be removed in version 2.13. Deprecation warnings can be disabled by setting 

 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht4]
 ok: [cepht3]
 ok: [cepht5]
 ## TASK [ceph-rgw : create rgw keyrings] ***
 ok: [cepht1] => (item=None)
 ok: [cepht2] => (item=None)
 ok: [cepht3] => (item=None)
 ok: [cepht4] => (item=None)
 ok: [cepht5] => (item=None)
 ok: [cepht1] => (item=None)
 ok: [cepht1]
 ok: [cepht2] => (item=None)
 ok: [cepht3] => (item=None)
 ok: [cepht4] => (item=None)
 ok: [cepht4]
 ok: [cepht5] => (item=None)
 ok: [cepht5]
 ok: [cepht2] => (item=None)
 ok: [cepht2]
 ok: [cepht3] => (item=None)
 ok: [cepht3]
 ## TASK [ceph-rgw : include_tasks multisite] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-handler : set_fact multisite_called_from_handler_role] ***
 ok: [cepht1]
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht5]
 ## TASK [ceph-crash : create client.crash keyring] ***
 changed: [cepht1 -> cepht1]
 ## TASK [ceph-facts : check if podman binary is present] ***
 ok: [cepht2 -> cepht1]
 ok: [cepht4 -> cepht1]
 ok: [cepht3 -> cepht1]
 ok: [cepht1 -> cepht1]
 ok: [cepht5 -> cepht1]
 ## TASK [ceph-facts : set_fact container_binary] ***
 ok: [cepht1 -> cepht1]
 ok: [cepht2 -> cepht1]
 ok: [cepht3 -> cepht1]
 ok: [cepht4 -> cepht1]
 ok: [cepht5 -> cepht1]
 ## TASK [ceph-crash : set_fact container_exec_cmd] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-crash : get keys from monitors] ***
 ok: [cepht1 -> cepht1]
 ## TASK [ceph-crash : copy ceph key(s) if needed] ***
 ok: [cepht1]
 changed: [cepht2]
 changed: [cepht5]
 changed: [cepht4]
 changed: [cepht3]
 ## TASK [ceph-crash : create /var/lib/ceph/crash/posted] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [ceph-crash : include_tasks systemd.yml] ***
 skipping: [cepht1]
 skipping: [cepht2]
 skipping: [cepht3]
 skipping: [cepht4]
 skipping: [cepht5]
 ## TASK [start the ceph-crash service] ***
 ok: [cepht2]
 ok: [cepht3]
 ok: [cepht4]
 ok: [cepht1]
 ok: [cepht5]
 ## TASK [set ceph crash install 'Complete'] ***
 ok: [cepht1]
 # PLAY [mons] ***
 ## TASK [get ceph status from the first monitor] ***
 ok: [cepht1 -> cepht1]
 ## TASK [show ceph status for cluster ceph] ***
 ok: [cepht1 -> cepht1] => 


094'



t3,cepht4,cepht5 (age 5m)'
cepht4, cepht5, cepht2, cepht1'
nce 3m)'
cepht1.client-1, cepht2.client-0, cepht2.client-1, cepht2.master, cepht3.client-0, cepht3.client-1, cepht3.es, cepht4.client-0, cepht4.client-1, cepht5.client-0, cepht5.client-1)'






vail'


 # PLAY RECAP ***
 cepht1                     : ok=484  changed=60   unreachable=0    failed=0    skipped=774  rescued=0    ignored=0   
 cepht2                     : ok=355  changed=38   unreachable=0    failed=0    skipped=695  rescued=0    ignored=0   
 cepht3                     : ok=355  changed=38   unreachable=0    failed=0    skipped=708  rescued=0    ignored=0   
 cepht4                     : ok=416  changed=60   unreachable=0    failed=0    skipped=737  rescued=0    ignored=0   
 cepht5                     : ok=363  changed=41   unreachable=0    failed=0    skipped=693  rescued=0    ignored=0   
 INSTALLER STATUS ***
 Install Ceph Monitor           : Complete (0:00:45)
 Install Ceph Manager           : Complete (0:00:40)
 Install Ceph OSD               : Complete (0:00:53)
 Install Ceph RGW               : Complete (0:01:13)
 Install Ceph Dashboard         : Complete (0:00:47)
 Install Ceph Grafana           : Complete (0:00:40)
 Install Ceph Node Exporter     : Complete (0:00:21)
 Install Ceph Crash             : Complete (0:00:13)
 =============================================================================== 
 ceph-common : install redhat ceph packages ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 56.03s
 ceph-rgw : create replicated pools for rgw ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 30.19s
 ceph-mon : waiting for the monitor(s) to form the quorum... ------------------------------------------------------------------------------------------------------------------------------------------------------------------- 20.76s
 ceph-osd : use ceph-volume to create bluestore osds --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 12.84s
 ceph-osd : wait for all osd to be up ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 11.11s
 install ceph-mgr packages on RedHat or SUSE ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 7.08s
 ceph-dashboard : create dashboard admin user ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 6.62s
 ceph-rgw : create the zone user(s) --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 6.15s
 ceph-mgr : wait for all mgr to be up ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 6.09s
 ceph-dashboard : create radosgw system user ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 5.99s
 ceph-prometheus : start prometheus services ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 5.78s
 ceph-grafana : start the grafana-server service -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 5.52s
 ceph-rgw : create ec pools for rgw --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 4.22s
 ceph-mgr : create ceph mgr keyring(s) on a mon node ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 3.31s
 ceph-prometheus : service handler ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 2.96s
 ceph-dashboard : config the current dashboard backend -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 2.93s
 ceph-node-exporter : start the node_exporter service --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 2.92s
 gather and delegate facts ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 2.90s
 ceph-mgr : disable ceph mgr enabled modules ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 2.26s
 ceph-osd : set noup flag ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 2.09s
