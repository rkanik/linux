# Install

`sudo apt update`

`sudo apt install mysql-server`

`sudo systemctl start mysql.service`

`systemctl status mysql.service`

`sudo systemctl start mysql`

`sudo systemctl stop mysql`

`sudo mysql_secure_installation`

`CREATE USER 'rkanik'@'localhost' IDENTIFIED BY '12345678';`

`GRANT ALL PRIVILEGES ON *.* TO 'rkanik'@'localhost' WITH GRANT OPTION;`
