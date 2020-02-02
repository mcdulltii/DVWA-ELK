# DVWA-ELK

mysql -pPassw0rd!
CREATE USER 'dvwa'@'%' IDENTIFIED BY 'Passw0rd!';
CREATE DATABASE dvwa;
GRANT ALL PRIVILEGES ON dvwa.* TO 'dvwa'@'%';