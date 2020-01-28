
### update first
sudo apt-get update && sudo apt-get upgrade -y

### install apache2
sudo apt install apache2 -y

### install mysql
sudo apt install mysql-server
sudo apt install apache2 -y

### install php
sudo apt install php-pear php-fpm php-dev php-zip php-curl php-xmlrpc php-gdphp-mysql php-mbstring php-xml libapache2-mod-php
sudo service apache2 restart

### php smoke test
php -r 'echo "\n\nYour PHP installation is working fine.\n\n\n";'
sudo apt-get update && sudo apt-get update -y

### adds password access to mysql????

mysql_secure_installation
sudo su
phpenmod mbstring
sudo su
mysql -u ubuntu -p
sudo mysql
mysql -u ubuntu -p
mysql -u root -p
sudo mysql -p -u root

### install wordpress

sudo apt update && sudo apt upgrade -y

wget  http://wordpress.org/latest.tar.gz
wget  https://wordpress.org/latest.tar.gz
ls
tar -xzvf latest.tar.gz 
ls
rm latest.tar.gz 
ls
sudo mv wordpress/ /var/www/html/
ls
cd /var/www/html
ls
cd wordpress/
ls
sudo vim wp-config.php
cd wp-content/
ls
cd ..
ls
la
ls -la
cd ..
ls
ls -la
chmod +w wordpress/
ls -la
chmod +w wordpress/
ls -la
cd ..
lss
ls
ls -la
chmod +w html/
sudo chmod +w html/
ls
ls -la
chown -R ubuntu:html
cd
sudo chown -R www-data:www-data /var/www/wordpress
sudo chown -R www-data:www-data /var/www/html/wordpress/
c
his