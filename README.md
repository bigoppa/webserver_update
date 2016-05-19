# webserver_update
# webserver_update
#!bin/bash
sudo su -
yum -y update
yum -y install httpd
yum -y install wget
yum -y install zip
yum -y install unzip
cd /var/www/html/
wget http://54.174.195.190/index.html
service httpd on
service httpd start
