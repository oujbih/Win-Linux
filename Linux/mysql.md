
## deleting mysql database by accident
```
sudo apt update
sudo apt remove mariadb-server
sudo apt install mariadb-server
sudo /etc/init.d/mysql start
sudo mysql_secure_installation
```


## creat user 
```
CREATE DATABASE backup; USE backup; CREATE TABLE backup (name VARCHAR(2000));
CREATE USER 'backup'@'10.10.10.187' IDENTIFIED BY '<YOUR PASSWORD>';
GRANT ALL PRIVILEGES ON backup.* TO 'backup'@'10.10.10.187';
sudo nano /etc/mysql/mariadb.conf.d/50-server.cnf 
```
