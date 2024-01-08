# MariaDB --

How to install mariadb in ubuntu
* user the following command to install mariaDB
```
sudo apt install mariadb-server
```
Output
```
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libevent-core-2.1-7 libevent-pthreads-2.1-7 libmecab2 libprotobuf-lite23 mecab-ipadic
  mecab-ipadic-utf8 mecab-utils
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  libdbd-mysql-perl libmariadb3 libmysqlclient21 mariadb-client-10.6 mariadb-client-core-10.6
  mariadb-common mariadb-server-10.6 mariadb-server-core-10.6
Suggested packages:
  mailx mariadb-test
The following NEW packages will be installed:
  libdbd-mysql-perl libmariadb3 libmysqlclient21 mariadb-client-10.6 mariadb-client-core-10.6
  mariadb-common mariadb-server mariadb-server-10.6 mariadb-server-core-10.6
0 upgraded, 9 newly installed, 0 to remove and 3 not upgraded.
Need to get 0 B/15.8 MB of archives.
After this operation, 156 MB of additional disk space will be used.
Do you want to continue? [Y/n] 
Preconfiguring packages ...
Selecting previously unselected package mariadb-common.
(Reading database ... 259303 files and directories currently installed.)
Preparing to unpack .../mariadb-common_1%3a10.6.12-0ubuntu0.22.04.1_all.deb ...
Unpacking mariadb-common (1:10.6.12-0ubuntu0.22.04.1) ...
Selecting previously unselected package libmariadb3:amd64.
Preparing to unpack .../libmariadb3_1%3a10.6.12-0ubuntu0.22.04.1_amd64.deb ...
Unpacking libmariadb3:amd64 (1:10.6.12-0ubuntu0.22.04.1) ...
Selecting previously unselected package mariadb-client-core-10.6.
Preparing to unpack .../mariadb-client-core-10.6_1%3a10.6.12-0ubuntu0.22.04.1_amd64.deb ...
Unpacking mariadb-client-core-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Selecting previously unselected package mariadb-client-10.6.
Preparing to unpack .../mariadb-client-10.6_1%3a10.6.12-0ubuntu0.22.04.1_amd64.deb ...
Unpacking mariadb-client-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Selecting previously unselected package mariadb-server-core-10.6.
Preparing to unpack .../mariadb-server-core-10.6_1%3a10.6.12-0ubuntu0.22.04.1_amd64.deb ...
Unpacking mariadb-server-core-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Setting up mariadb-common (1:10.6.12-0ubuntu0.22.04.1) ...
update-alternatives: using /etc/mysql/mariadb.cnf to provide /etc/mysql/my.cnf (my.cnf) in auto
 mode
Selecting previously unselected package mariadb-server-10.6.
(Reading database ... 259514 files and directories currently installed.)
Preparing to unpack .../mariadb-server-10.6_1%3a10.6.12-0ubuntu0.22.04.1_amd64.deb ...
/var/lib/mysql: found previous version 8.0
The file /var/lib/mysql/debian-8.0.flag indicates a
version that cannot automatically be upgraded. Therefore the
previous data directory will be renamed to /var/lib/mysql-8.0 and
a new data directory will be initialized at /var/lib/mysql.
Please manually export/import your data (e.g. with mysqldump) if needed.
Unpacking mariadb-server-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Selecting previously unselected package libmysqlclient21:amd64.
Preparing to unpack .../libmysqlclient21_8.0.35-0ubuntu0.22.04.1_amd64.deb ...
Unpacking libmysqlclient21:amd64 (8.0.35-0ubuntu0.22.04.1) ...
Selecting previously unselected package libdbd-mysql-perl:amd64.
Preparing to unpack .../libdbd-mysql-perl_4.050-5ubuntu0.22.04.1_amd64.deb ...
Unpacking libdbd-mysql-perl:amd64 (4.050-5ubuntu0.22.04.1) ...
Selecting previously unselected package mariadb-server.
Preparing to unpack .../mariadb-server_1%3a10.6.12-0ubuntu0.22.04.1_all.deb ...
Unpacking mariadb-server (1:10.6.12-0ubuntu0.22.04.1) ...
Setting up libmysqlclient21:amd64 (8.0.35-0ubuntu0.22.04.1) ...
Setting up libdbd-mysql-perl:amd64 (4.050-5ubuntu0.22.04.1) ...
Setting up libmariadb3:amd64 (1:10.6.12-0ubuntu0.22.04.1) ...
Setting up mariadb-server-core-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Setting up mariadb-client-core-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Setting up mariadb-client-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Setting up mariadb-server-10.6 (1:10.6.12-0ubuntu0.22.04.1) ...
Installing new version of config file /etc/mysql/debian-start ...
renamed '/etc/logrotate.d/mysql-server' -> '/etc/logrotate.d/mysql-server.dpkg-bak'
Created symlink /etc/systemd/system/multi-user.target.wants/mariadb.service → /lib/systemd/syst
em/mariadb.service.
Setting up mariadb-server (1:10.6.12-0ubuntu0.22.04.1) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for libc-bin (2.35-0ubuntu3.5) ...
```

* Secure your MariaDB installation
```
sudo mysql_secure_installation
```
Output
```

NOTE: RUNNING ALL PARTS OF THIS SCRIPT IS RECOMMENDED FOR ALL MariaDB
      SERVERS IN PRODUCTION USE!  PLEASE READ EACH STEP CAREFULLY!

In order to log into MariaDB to secure it, we'll need the current
password for the root user. If you've just installed MariaDB, and
haven't set the root password yet, you should just press enter here.

Enter current password for root (enter for none): 
OK, successfully used password, moving on...

Setting the root password or using the unix_socket ensures that nobody
can log into the MariaDB root user without the proper authorisation.

You already have your root account protected, so you can safely answer 'n'.

Switch to unix_socket authentication [Y/n] n
 ... skipping.

You already have your root account protected, so you can safely answer 'n'.

Change the root password? [Y/n] n
 ... skipping.

By default, a MariaDB installation has an anonymous user, allowing anyone
to log into MariaDB without having to have a user account created for
them.  This is intended only for testing, and to make the installation
go a bit smoother.  You should remove them before moving into a
production environment.

Remove anonymous users? [Y/n] n
 ... skipping.

Normally, root should only be allowed to connect from 'localhost'.  This
ensures that someone cannot guess at the root password from the network.

Disallow root login remotely? [Y/n] 
 ... Success!

By default, MariaDB comes with a database named 'test' that anyone can
access.  This is also intended only for testing, and should be removed
before moving into a production environment.

Remove test database and access to it? [Y/n] 
 - Dropping test database...
 ... Success!
 - Removing privileges on test database...
 ... Success!

Reloading the privilege tables will ensure that all changes made so far
will take effect immediately.

Reload privilege tables now? [Y/n] 
 ... Success!

Cleaning up...

All done!  If you've completed all of the above steps, your MariaDB
installation should now be secure.

Thanks for using MariaDB!
```

* Start and enable MariaDB
Installation is complete, start the MariaDB service and enable it to start on boot:

```
sudo syatemctl status mariadb
```
Output
```
● mariadb.service - MariaDB 10.6.12 database server
     Loaded: loaded (/lib/systemd/system/mariadb.service; enabled; vendor preset: en>
     Active: active (running) since Mon 2024-01-08 14:28:18 IST; 1h 37min ago
       Docs: man:mariadbd(8)
             https://mariadb.com/kb/en/library/systemd/
   Main PID: 27654 (mariadbd)
     Status: "Taking your SQL requests now..."
      Tasks: 9 (limit: 4365)
     Memory: 61.5M
        CPU: 2.204s
     CGroup: /system.slice/mariadb.service
             └─27654 /usr/sbin/mariadbd

Jan 08 14:28:18 bhandari mariadbd[27654]: 2024-01-08 14:28:18 0 [Note] InnoDB: Buffe>
Jan 08 14:28:18 bhandari mariadbd[27654]: 2024-01-08 14:28:18 0 [Note] Server socket>
Jan 08 14:28:18 bhandari mariadbd[27654]: 2024-01-08 14:28:18 0 [Note] /usr/sbin/mar>
lines 1-16
```

or 
```
sudo systemctl enable mariadb
```

* To check if MariaDB is running properly, you can use the following command:
```
sudo systemctl start mariadb
```
* How to accessing the MariaDB shell
```
sudo mariadb
```
Output
```
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 39
Server version: 10.6.12-MariaDB-0ubuntu0.22.04.1 Ubuntu 22.04

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

MariaDB [(none)]> 
```
* How ro show database
```
show databases;
```
Output
```
MariaDB [(none)]> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
4 rows in set (0.003 sec)

MariaDB [(none)]> 
```

* How to create database
```
create database demo;
```
output
```
MariaDB [(none)]> create database demo
    -> ;
Query OK, 1 row affected (0.001 sec)
```
 again confermation your database in created  
 show database
```
show database
```
output
```
MariaDB [(none)]> show databases;
+--------------------+
| Database           |
+--------------------+
| demo               |
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
5 rows in set (0.001 sec)
```
how to drop database
```
drop database demo;
```

output
```
MariaDB [(none)]> drop database demo;
Query OK, 0 rows affected (0.005 sec)

MariaDB [(none)]> 
```

Again confirmation
```
show databases;
```
Output
```
MariaDB [(none)]> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
4 rows in set (0.001 sec)

MariaDB [(none)]> 
```

* How to create table on the database
```
create table book (ID INT ,name varchar (20),email varchar(25));
```

* How to insert data in the table
  
```
insert into book (id,name,email) values(1,"Deepak","abc@gmail.com");
```

Output:
```
MariaDB [text]>  insert into book (id,name,email) values(1,"Deepak","abc@gmail.com");
Query OK, 1 row affected (0.002 sec)

MariaDB [text]> 
```
* How to show data in the book table  

```
select * from book;
```
output
```
MariaDB [text]> select * from book;
+------+--------+---------------+
| ID   | name   | email         |
+------+--------+---------------+
|    1 | Deepak | abc@gmail.com |
+------+--------+---------------+
1 row in set (0.001 sec)

MariaDB [text]> 
```

* How to exit mariadb sell
```
quit
```
and 

```
exit
```


