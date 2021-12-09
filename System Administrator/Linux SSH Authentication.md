### SSH access to all app servers through their respective sudo users

```
ssh-keygen -t rsa

ssh-copy-id tony@stapp01
ssh-copy-id steve@stapp02
ssh-copy-id banner@stapp03

## test
ssh 'tony@stapp01'
ssh 'steve@stapp02'
ssh 'banner@stapp03'

who i am

```
