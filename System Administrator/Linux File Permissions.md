<https://kodekloudhub.github.io/kodekloud-engineer/docs/projects/nautilus>

```
thor@jump_host ~$ ssh tony@stapp01
[tony@stapp01 ~]$ sudo -i
[root@stapp01 ~]# ll /tmp/xfusioncorp.sh 
---------- 1 root root 40 Nov 28 11:45 /tmp/xfusioncorp.sh
[root@stapp01 ~]# chmod a+rx /tmp/xfusioncorp.sh 
[root@stapp01 ~]# ll /tmp/xfusioncorp.sh 
-r-xr-xr-x 1 root root 40 Nov 28 11:45 /tmp/xfusioncorp.sh
[root@stapp01 ~]# exit
logout
[tony@stapp01 ~]$ ll /tmp/xfusioncorp.sh 
-r-xr-xr-x 1 root root 40 Nov 28 11:45 /tmp/xfusioncorp.sh
[tony@stapp01 ~]$ cd tmp
[tony@stapp01 ~]$ cd /tmp/
[tony@stapp01 tmp]$ ./xfusioncorp.sh 
Welcome To KodeKloud
[tony@stapp01 tmp]$ 
```
