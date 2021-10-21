# setup_vps
kumpulan link tutorial setup vps

install vesta cp
https://vestacp.com/install/
sample :
# Connect to your server as root via SSH ssh 
root@your.server
# Download installation script 
curl -O http://vestacp.com/pub/vst-install.sh
# Run it 
bash vst-install.sh --nginx yes --apache yes --phpfpm no --named yes --remi no --vsftpd yes --proftpd no --iptables no --fail2ban no --quota no --exim no --dovecot no --spamassassin no --clamav no --softaculous no --mysql yes --postgresql no --hostname namadomain.com --email email@gmail.com --password pass123

# upgrade vesta cp php 5.6 to 7.4 centos 7
# wget http://rpms.remirepo.net/enterprise/remi-release-7.rpm
# rpm -Uvh  remi-release-7.rpm
# yum install yum-utils
# yum-config-manager --enable remi-php74
# yum update -y 
# php -v
tutor: https://www.techtransit.org/upgrade-php-5-4-or-5-6-to-php-7-on-vestacp-centos-rhel-vesta-panel/

install CMS Wordpress.

plugin simple
LiteSpeed Cache
Yoast SEO
UpdraftPlus - Backup/Restore
WPS Hide Login

Install PHP OPCache APC/APCu Memcached on VestaCP CentOS
https://forum.vestacp.com/viewtopic.php?t=17590

https://blog.bodi.web.id/optimasi-mysql-database-pada-small-vps.html

tuning mysql
https://forum.vestacp.com/viewtopic.php?t=5456

optimize apache
https://www.mysterydata.com/how-to-improve-and-speed-up-the-performance-of-apache-in-vestacp/
or read
https://forum.vestacp.com/viewtopic.php?t=17584
