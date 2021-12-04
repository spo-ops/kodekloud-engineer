### Disable Root Login

```
cat /etc/ssh/sshd_config
vi $_
PermitRootLogin yes to no

systemctl restart sshd
logout

ssh root@stapp01
root@stapp01's password: 
Permission denied, please try again.

```
