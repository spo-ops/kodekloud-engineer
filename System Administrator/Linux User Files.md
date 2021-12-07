## Linux User Files

```
ssh steve@stapp02
sudo -i

cd /home/usersdata
find . -user anita
find . -user anita | cpio -pdm /blog
cd blog
ls



```
