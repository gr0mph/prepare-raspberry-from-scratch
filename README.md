From Linux

Intall Etcher
https://doc.ubuntu-fr.org/etcher

Download last Raspbian
https://www.raspberrypi.org/downloads/raspbian/

Use Etcher
- Select iso image (need extract zip file before)
- Flash SD card with iso image
- Wait


Install Ansible
https://www.cyberciti.biz/python-tutorials/linux-tutorial-install-ansible-configuration-management-and-it-automation-tool/

$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible

Install OpenSSH

sudo apt-get install openssh-server
[systemctl restart ssh.service]

https://www.linuxtrainingacademy.com/ssh-login-without-password/

(maybe) under raspberry
cd; ssh-keygen -t RSA -b 4096; cat .ssh/id_rsa.pub > .ssh/authorized_keys



Market:
- USB All in one product
- SDHC Card 32 Go
