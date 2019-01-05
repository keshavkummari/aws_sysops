#!/bin/bash
cd /opt/
yum install wget* curl* vim* unzip* -y
yum update -y
wget https://www.free-css.com/assets/files/free-css-templates/download/page231/bizexpress-v1.0.1.zip
unzip *.zip
cd Biz*
yum install http* --skip-broken -y
mv * /var/www/html/
service httpd start
# systemct start httpd.service
