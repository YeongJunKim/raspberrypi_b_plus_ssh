# raspberrypi_b_plus_ssh
raspberrypi_b_plus_ssh

#### IP address ?
```
$ hostname -I
```



#### Install ?
```
$ sudo apt install openssh-server
$ sudo systemctl enable ssh.service
$ sudo systemctl start ssh.service
$ sudo dpkg-reconfigure openssh-server
```



#### Host key verification failed ?
```
$ sudo ssh-keygen -R [IP or DomainName]
```
