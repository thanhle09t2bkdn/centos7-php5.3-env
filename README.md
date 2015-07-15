```
Docker ubuntu 12.04 with LAMP(php5.3) image

Build image:
cd <clone folder>
./build

Usage:
1. Start container:
./start

2. Stop container:
./stop

Config:
In 'start' script has 3 params: 
+WEB_PORT: web mapping port, default 4000
+SSH_PORT: ssh mapping port, default 2000
+WWW_PATH: path of www of host machine, this folder will be mounted to container, default /var/www

```