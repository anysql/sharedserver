# Dynamic Thread Pool

1, Binary file only, compatible with MySQL community edition.

- thread_pool6_5562.so is for 5.5.62 on RHEL/CentOS 6+
- thread_pool6_5651.so is for 5.6.51 on RHEL/CentOS 6+
- thread_pool6_5636.so is for 5.7.36 on RHEL/CentOS 6+
- thread_pool6_8127.so is for 8.0.27 on RHEL/CentOS 6+
- shared_server6_5735.so is for percona 5.7.35 on RHEL/CentOS 6+

2, Copy the so file to "/usr/lib64/mysql/plugin" directory.

3, Set plugin-load option in my.cnf to load it.

- plugin-load = thread_pool<os_version>_<mysql_version>.so

4, Start your workload, it's ready for any workload.
