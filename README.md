# Thread Pool for MySQL Community Edition

Binary file only, compatible with MySQL community edition.

thread_pool6_5636.so is for 5.7.36 on RHEL/CentOS 6
thread_pool7_5636.so is for 5.7.36 on RHEL/CentOS 7
thread_pool6_8127.so is for 8.0.27 on RHEL/CentOS 6
thread_pool7_8127.so is for 8.0.27 on RHEL/CentOS 7

Copy the so file to "/usr/lib64/mysql/plugin" directory.

use plugin-load option in my.cnf to load it

plugin-load = thread_pool<os version>_<mysql_version>.so

