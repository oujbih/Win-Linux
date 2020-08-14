## installing wifi
```
git clone https://github.com/smlinux/rtl8723de.git -b current
dkms add ./rtl8723de
dkms install rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414
depmod -a
reboot
```
## install in debian
```
sudo apt install gdebi
sudo dpkg -i rstudio-1.3.959-amd64.deb
```
## Erorr dependencies
```
sudo apt install -f
```

## fontconfig.pc'to the PKG_CONFIG_PATH environment variable
```
apt-get install -y pkg-config lxc-dev
```
## R fix installing 
```
sudo apt-get install libssl-dev
```
## Bluetooth
```
sudo systemctl start bluetooth.service
```
## kali linux ctrl + up/down 
```
gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-down "['<Super>Page_Down']"
gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-up "['<Super>Page_Up']"
```
## Clipboard Indicator
```
System Settings --> Keyboard layout, tab Layouts --> Options... Key(s) to change layout
```
## Exclude packages from apt-get upgrade
```
sudo apt-mark hold burpsuite 
```
##  How do I shorten the current directory path shown on terminal?
```
vi .bashrc
\w Change that to \W (upper case)
```

## How do I create a permanent Bash alias?
```
code ~/.bashrc
```
