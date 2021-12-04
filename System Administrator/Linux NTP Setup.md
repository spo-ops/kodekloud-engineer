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

- you have not added the correct ntp server on App Server 3
-----------------------------------------------
stapp01	  172.16.238.10	  stapp01.stratos.xfusioncorp.com	  tony	  Ir0nM@n	  Nautilus App 1
stapp02	  172.16.238.11	  stapp02.stratos.xfusioncorp.com	  steve	  Am3ric@	  Nautilus App 2
stapp03	  172.16.238.12	  stapp03.stratos.xfusioncorp.com	  banner	BigGr33n	Nautilus App 3
