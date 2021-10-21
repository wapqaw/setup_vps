# setup_vps
kumpulan link tutorial setup vps

#install vesta cp
https://vestacp.com/install/<br/>
sample :<br/>
Connect to your server as root via SSH ssh <br/>
root@your.server<br/>
Download installation script <br/>
curl -O http://vestacp.com/pub/vst-install.sh<br/>
bash vst-install.sh --nginx yes --apache yes --phpfpm no --named yes --remi no --vsftpd yes --proftpd no --iptables no --fail2ban no --quota no --exim no --dovecot no --spamassassin no --clamav no --softaculous no --mysql yes --postgresql no --hostname namadomain.com --email email@gmail.com --password pass123<br/>

# upgrade vesta cp php 5.6 to 7.4 centos 7
wget http://rpms.remirepo.net/enterprise/remi-release-7.rpm<br/>
rpm -Uvh  remi-release-7.rpm<br/>
yum install yum-utils<br/>
yum-config-manager --enable remi-php74<br/>
yum update -y<br/>
php -v<br/>
tutor: https://www.techtransit.org/upgrade-php-5-4-or-5-6-to-php-7-on-vestacp-centos-rhel-vesta-panel/

# install CMS Wordpress.

plugin simple :<br/>
LiteSpeed Cache<br/>
Yoast SEO<br/>
UpdraftPlus - Backup/Restore<br/>
WPS Hide Login<br/>

# Install PHP OPCache APC/APCu Memcached on VestaCP CentOS
https://forum.vestacp.com/viewtopic.php?t=17590<br/>

# tuning mysql
https://blog.bodi.web.id/optimasi-mysql-database-pada-small-vps.html<br/>
https://forum.vestacp.com/viewtopic.php?t=5456<br/>

# optimize apache
https://www.mysterydata.com/how-to-improve-and-speed-up-the-performance-of-apache-in-vestacp/<br/>
or read<br/>
https://forum.vestacp.com/viewtopic.php?t=17584<br/>
