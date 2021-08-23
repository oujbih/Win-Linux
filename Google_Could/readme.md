```
sudo apt update
sudo apt install ubuntu-desktop
wget https://download.nomachine.com/download/7.6/Linux/nomachine_7.6.2_4_amd64.deb

sudo -s
passwd  # add password to root user
nano /etc/ssh/sshd_config # change No to Yes 
adduser oujbih
usermod -a -G sudo,adm oujbih
reboot 
```
