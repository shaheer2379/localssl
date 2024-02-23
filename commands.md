
*******************************
Commands used in this tutorial
******************************
sudo -s
apt install apache2 -y
mkdir /var/www/dev
nano /var/www/dev/index.html
chmod -R 755 /var/www/dev
chown -R www-data. /var/www/dev
nano /etc/apache2/sites-avaialble/dev.conf
a2ensite dev.conf
systemctl restart apache2
nano /etc/hosts
nano /etc/apache2/sites-avaialble/dev-ssl.conf
a2enmod ssl
a2ensite dev-ssl.conf
a2enmod proxy
a2enmod proxy_http
a2enmod proxy_wstunnel
a2enmod rewrite