
There is a critical issue going on with the Nautilus application in Stratos DC. 
The production support team identified that the application is unable to connect to the database. 
After digging into the issue, the team found that mariadb service is down on the database server.



Look into the issue and fix the same.
```
ssh peter@stdb01
sudo -i

systemctl status mariadb -l
ll /var/lib
mv /var/lib/mysqld /var/lib/mysql
systemctl start mariadb
systemctl status mariadb -l

```
that's it.
