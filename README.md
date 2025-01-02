# Perfect-World-1.7.3

​Good Day . My name is Dragenheard

i work hard every day on my Perfect world Servers my best Project is 1.7.3, olso i work on 1.7.6 but its works not right at now.

### 1.7.3 has  a few bugs, but i ill fixed


# how to install (ubuntu 22 and Debian 11)

## architecture i386
````
dpkg --add-architecture i386; apt update && apt upgrade -y
````

## Software you ill need

````
apt-get install -y libstdc++6:i386 libxml2:i386 mariadb-server apache2 phpmyadmin php-mbstring php-zip php-gd php-json php-curl default-jdk p7zip-full
````


## Setup Mariadb
````
mysql_secure_installation
````

# Install server

## Download the Server
````
https://drive.google.com/file/d/1-BE0Btosp9lH67maFbWreESQgf3eDcTK/view?usp=drive_link
````

# Upload to /
````
cd /; 7z x Perfect_World_Server_1.7.3.zip
````

# add the Server to the /etc/hosts
````
nano /etc/hosts
````

# put this into /etc/hosts 
````
# Perfect World

127.0.0.1    gm_server

127.0.0.1    PW-Server

127.0.0.1    aumanager

127.0.0.1    manager

127.0.0.1    link1

127.0.0.1    game1

127.0.0.1    game2

127.0.0.1    delivery

127.0.0.1    database

127.0.0.1    backup

127.0.0.1    auth

127.0.0.1    audb

127.0.0.1    gmserver

127.0.0.1    LOCAL0

127.0.0.1    LogServer

127.0.0.1    AUDATA
````

# enter your database user and password to authd
````
nano /home/authd/table.xml
````


to install pwadmin see here ​Simple pwadmin installer by crucifix​​​

https://forum.ragezone.com/threads/pwadmin-remix-version-1.1238670/


# give rihgts to the server
````
cd /home/; chmod 777 -R *
````

# to manage the server

# start the server
````
./server start
````

### stopping the server
````
./server stop 
````

### show its the server runs
````
./server status
````


# Have fun and njoy my Project
