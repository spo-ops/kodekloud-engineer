### Linux NTP Setup


```
yum install ntp -y
vi /etc/ntp.conf

server 1.sg.poo;.ntp.org

systemctl enable ntpd
systemctl start ntpd
systemctl status ntpd
ntpstat

systemctl restart ntpd
ntpstat

```
