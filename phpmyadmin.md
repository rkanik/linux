# Install

`sudo apt update`

`sudo apt install phpmyadmin php-mbstring php-zip php-gd php-json php-curl`

`sudo mysql`

`UNINSTALL COMPONENT "file://component_validate_password";`

`INSTALL COMPONENT "file://component_validate_password";`

`sudo apt install phpmyadmin`

```
sudo a2enmod proxy_fcgi setenvif
sudo a2enconf php8.1-fpm
sudo service apache2 restart
```