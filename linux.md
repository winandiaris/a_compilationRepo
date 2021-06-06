## UBUNTU

## CENTOS
### DIRECTORY MOVEMENT
- ls --> lists the contents of the directory
- ll --> lists the contents of the directory length-wise
- cp --> copies a file
  - cp -r /home/server/folder/test/. /home/server/  --> copy direktori dan isi ke tempat lain
- mv --> moves a directory
  - mv /home/server/folder/test/ /home/server/folder/tes2/ --> cut folder/rename folder
  - mv /home/server/folder/test/* /home/server/folder/tes2 --> cut semua isi test ke folder test2 tenpa menghapus folder test
  - mv -f /path/subfolder/{.,}* /path/ --> termask hidden folder
- rm --> hapus
  - rm tes/file.txt --> hapus file
  - rm -r tes --> hapus folder dan isinya
- cd .. --> moves up one directory
- cd ~ --> moves to home directory
- pwd --> present working directory
- find --> search given directory for namestring and display it

### USER MANAGEMENT
- alias --> creates an alias
- passwrd --> updates user authentication
- useradd --> adds a new user
- sudo --> admin privileges
- who --> shows currently logged on users
- groupadd --> create new group
- uname --> print system info

 ### SYSTEM MANAGEMENT
- apropos --> search set of database files and display result as standard output
- bcwipe --> repeatedly overwrite special patterns onto to-be-destroyed files
- chkconfig  --> update and query run level info for system services
- dstat --> displays real-time system stats
- fdisk --> disk partioning utility
- mount --> mounts a filesystem
- grep --> search named input files for lines containing match to given pattern, then print
- hostname --> displays current host/domain/node name
- ifconfig --> configure networking interface
- ifdown --> manually take down an interface
- iftop --> shows bandwidth usage of interface
- ifup --> brings interface back up
- kill --> terminate a running process
- ps --> list of currently running processe and their process IDs
- man --> manual page for particular command/tool
- systemcl --> may be used to introspect and control the state of the "systemd" system and service manager
- tail --> used to output last part of a file, seful on log files

### FILE MANAGEMENT
- chmod --> change permissions of a file
- chown --> change the ownership of a file
- diff --> compare two files against each other
- du --> displays disk usage of a directory
- rm --> removes files/directories
- find --> search given directory for namestring and display it
- nano
- vi/vim

### YUM
- yum list updates
- yum update
- yum update --security --> hanya update security
- sudo yum update httpd --> update package tertentu
- yum list installed
- yum list installed docker --> cek package terintall atau tidak
- yum list | grep docker
- yum install nginx mariadb-server php-fpm
- sudo yum localinstall foo.rpm --> install dari local file 
- sudo yum https://server1.cyberciti.biz/foo.rpm --> dari http mirror
- yum downgrade nginx
- yum reinstall httpd
- yum remove httpd --> uninstall
- yum grouplist
- yum groupinstall "Development Tools"
- yum groupupdate "Development Tools"
- yum groupremove "Development Tools"
- yum groupinfo 'Development Tools'
