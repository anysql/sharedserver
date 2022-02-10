# SharedServer - A Thread Pool Replacement

1, Binary file only, compatible with MySQL community edition.

- sharedserver_c6_m5562.so is for MySQL 5.5.62 on RHEL/CentOS 6
- sharedserver_c6_m5651.so is for MySQL 5.6.51 on RHEL/CentOS 6
- sharedserver_c6_m5736.so is for MySQL 5.7.36 on RHEL/CentOS 6
- sharedserver_c6_m8027.so is for MySQL 8.0.27 on RHEL/CentOS 6
- sharedserver_c7_m5736.so is for MySQL 5.7.36 on RHEL/CentOS 7
- sharedserver_c7_m8027.so is for MySQL 8.0.27 on RHEL/CentOS 7
- sharedserver_c6_p5562.so is for percona 5.5.62 on RHEL/CentOS 6
- sharedserver_c6_p5651.so is for percona 5.6.51 on RHEL/CentOS 6
- sharedserver_c6_p5735.so is for percona 5.7.35 on RHEL/CentOS 6
- sharedserver_c6_p8026.so is for percona 8.0.26 on RHEL/CentOS 6

2, Copy the so file to "/usr/lib64/mysql/plugin" directory.

3, Set plugin-load option in my.cnf to load it.

- plugin-load = sharedserver_c<os_version>_<mysql_version>.so

4, Start your workload, it's ready for any workload.
