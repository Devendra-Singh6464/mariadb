# MariaDB --

Mariadb is a relational database management system that stores information in a structured way. It organizes data into tables, where each table consists of rows and columns.

## Prerequisite

Distributor ID:	Ubuntu  
Description:	Ubuntu 22.04.3 LTS  
Release:	22.04  
Codename:	jammy  

### Command-
```
sudo apt-get update
```
### Output-
```
deepak@bhandari:~$ sudo apt-get update
[sudo] password for deepak: 
Hit:1 https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/jammy pgadmin4 InRelease
Hit:2 https://apt.postgresql.org/pub/repos/apt jammy-pgdg InRelease            
Get:3 http://ppa.launchpad.net/tektoncd/cli/ubuntu eoan InRelease [15.9 kB]    
Err:3 http://ppa.launchpad.net/tektoncd/cli/ubuntu eoan InRelease              
  The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 3EFE0E0A2F2F60AA
Get:4 https://download.docker.com/linux/ubuntu jammy InRelease [48.8 kB]       
Get:5 http://packages.microsoft.com/repos/code stable InRelease [3,589 B]      
Get:6 https://download.docker.com/linux/ubuntu jammy/stable amd64 Packages [25.1 kB]
Get:7 https://dl.google.com/linux/chrome/deb stable InRelease [1,825 B]        
Get:8 http://packages.microsoft.com/repos/code stable/main amd64 Packages [16.1 kB]
Ign:9 https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/4.4 InRelease      
Get:10 http://packages.microsoft.com/repos/code stable/main arm64 Packages [16.2 kB]
Get:11 http://packages.microsoft.com/repos/code stable/main armhf Packages [16.3 kB]
Ign:12 https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0 InRelease     
Get:13 https://dl.google.com/linux/chrome/deb stable/main amd64 Packages [1,078 B]
Hit:14 https://ppa.launchpadcontent.net/deadsnakes/ppa/ubuntu jammy InRelease  
Get:15 http://security.ubuntu.com/ubuntu jammy-security InRelease [110 kB]     
Hit:16 http://in.archive.ubuntu.com/ubuntu jammy InRelease                     
Get:17 https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/4.4 Release [3,094 B]
Get:18 https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0 Release [3,094 B]
Get:19 http://in.archive.ubuntu.com/ubuntu jammy-updates InRelease [119 kB]    
Get:20 https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/4.4 Release.gpg [866 B]
Get:21 https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0 Release.gpg [866 B]
Get:22 https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/4.4/multiverse amd64 Packages [25.3 kB]
Get:23 https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/4.4/multiverse arm64 Packages [22.3 kB]
Get:24 https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0/multiverse amd64 Packages [66.0 kB]
Get:25 http://security.ubuntu.com/ubuntu jammy-security/main amd64 Packages [1,109 kB]
Get:26 https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0/multiverse arm64 Packages [59.8 kB]
Hit:27 http://in.archive.ubuntu.com/ubuntu jammy-backports InRelease           
Get:28 http://in.archive.ubuntu.com/ubuntu jammy-updates/main amd64 Packages [1,325 kB]
Get:29 http://security.ubuntu.com/ubuntu jammy-security/main i386 Packages [393 kB]
Get:30 http://security.ubuntu.com/ubuntu jammy-security/main Translation-en [207 kB]
Get:31 http://security.ubuntu.com/ubuntu jammy-security/restricted amd64 Packages [1,313 kB]
Get:32 http://security.ubuntu.com/ubuntu jammy-security/restricted Translation-en [214 kB]
Get:33 http://in.archive.ubuntu.com/ubuntu jammy-updates/main i386 Packages [560 kB]
Get:34 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 Packages [835 kB]
Get:35 http://in.archive.ubuntu.com/ubuntu jammy-updates/main Translation-en [267 kB]
Get:36 http://security.ubuntu.com/ubuntu jammy-security/universe i386 Packages [587 kB]
Get:37 http://in.archive.ubuntu.com/ubuntu jammy-updates/restricted amd64 Packages [1,342 kB]
Get:38 http://security.ubuntu.com/ubuntu jammy-security/universe Translation-en [159 kB]
Get:39 http://in.archive.ubuntu.com/ubuntu jammy-updates/restricted i386 Packages [34.8 kB]
Get:40 http://in.archive.ubuntu.com/ubuntu jammy-updates/restricted Translation-en [220 kB]
Get:41 http://in.archive.ubuntu.com/ubuntu jammy-updates/universe i386 Packages [685 kB]
Get:42 http://in.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 Packages [1,038 kB]
Get:43 http://in.archive.ubuntu.com/ubuntu jammy-updates/universe Translation-en [233 kB]
Get:44 http://in.archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 Packages [42.1 kB]
Reading package lists... Done                                                  
N: Skipping acquire of configured file 'main/binary-i386/Packages' as repository 'https://apt.postgresql.org/pub/repos/apt jammy-pgdg InRelease' doesn't support architecture 'i386'
W: GPG error: http://ppa.launchpad.net/tektoncd/cli/ubuntu eoan InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 3EFE0E0A2F2F60AA
E: The repository 'http://ppa.launchpad.net/tektoncd/cli/ubuntu eoan InRelease' is not signed.
N: Updating from such a repository can't be done securely, and is therefore disabled by default.
N: See apt-secure(8) manpage for repository creation and user configuration details.
W: https://repo.mongodb.org/apt/ubuntu/dists/jammy/mongodb-org/4.4/Release.gpg: Key is stored in legacy trusted.gpg keyring (/etc/apt/trusted.gpg), see the DEPRECATION section in apt-key(8) for details.
W: https://repo.mongodb.org/apt/ubuntu/dists/focal/mongodb-org/5.0/Release.gpg: Key is stored in legacy trusted.gpg keyring (/etc/apt/trusted.gpg), see the DEPRECATION section in apt-key(8) for details.
```

## Command -
```
sudo apt-get upgrade
```
## output-
```

```

> 
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

- Secure your MariaDB installation
* Configure mysql.  
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

* Start and enable MariaDB service.

```
sudo syatemctl start mariadb
```
```
sudo systemctl enable mariadb
```
Output -
```
deepak@bhandari:~$ sudo systemctl enable mariadb
[sudo] password for deepak: 
Synchronizing state of mariadb.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable mariadb
```

Output
* To check if MariaDB is active and not active:
```
sudo systemctl status mariadb
```
Output -

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
Please enable firewall -  
The Database Firewall filter is used to block queries that match a set of rules. It can be used to prevent harmful queries from reaching the backend database instances or to limit access to the database based on a more flexible set of rules compared to the traditional GRANT-based privilege system. Currently the filter does not support multi-statements.

- Apply the firewall rule.
```
firewall-cmd --permanent --add-service=mysql
```
```
firewall-cmd--reload
```

* If you not set mariadb root password in the mariadb installation so run this command and set the root password 
```
SET PASSWORD FOR 'root'@'localhost` = PASSWORD('123')
```
Output - 
```
MariaDB [(none)]> SET PASSWORD FOR 'root'@'localhost' = PASSWORD('123');
Query OK, 0 rows affected (0.027 sec)

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
And 
```
mysql -u root -i
```
 Output -
 ```
deepak@bhandari:~$ mysql -u root -p 
Enter password: 
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 54
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

* How to create User:
```
create user Student@localhost identified by 'book';
```
Output -

```
MariaDB [(none)]> create user Student@localhost identified by 'book';
Query OK, 0 rows affected (0.020 sec)

MariaDB [(none)]>
```
* How to going inside the my database table -
```
user text;
```
  

The following statement types will allways be allowed through when action is set to allow:

* COM_CHANGE_USER: The user is changed for an active connection
* COM_FIELD_LIST: Aliss fro the `SHOW TABLES;` query
* COM_INIT_DB: Alias for `USE <db>;`
* COM_PING: Server is pinged
* COM_PROCESS_INFO: Alias for `SHOW PROCESSLIST;`
* COM_PROCESS_KILL: Alias for `KILL <id>;` query
* COM_QUIT: Client closes connection
* COM_SET_OPTION: Client multi-statements are being configured
