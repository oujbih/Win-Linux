https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-18-04-bionic-beaver-linux

# 1  trying 
sudo apt install nvidia-prime

# 2 
https://www.cyberciti.biz/faq/ubuntu-linux-install-nvidia-driver-latest-proprietary-driver/


# 3 
sudo apt-get install firmware-linux

# 4
sudo apt install linux-generic
https://askubuntu.com/questions/1292278/nvidia-driver-is-installed-but-the-driver-is-not-loaded


# 5 tmp fix 
GRUB_DEFAULT="Advanced options for Ubuntu>Ubuntu, with Linux 5.11.0-40-generic"
sudo -H gedit /etc/default/grub
