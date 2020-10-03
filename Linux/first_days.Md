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
alias htbvpn='sudo openvpn ~/OUJBIH.ovpn;'
alias main='tmux split-window -h;tmux split-window;tmux select-pane -t 0;tmux rename-window main'
alias main2='tmux split-window -h;tmux split-window;tmux select-pane -t 0;tmux rename-window main2'
alias main3='tmux split-window -h;tmux split-window;tmux select-pane -t 0;tmux rename-window main3'
alias t1='tmux split-window -h'
alias t2='tmux split-window'
alias tk='tmux kill-window'
alias ports='netstat -tulanp'
alias tks='tmux kill-session --t'
alias codealias='code ~/.bashrc'
#https://www.cyberciti.biz/tips/bash-aliases-mac-centos-linux-unix.html
https://thoughtbot.com/blog/a-tmux-crash-course ## very good
```
## mail client Mailspring
```
sudo apt install libsecret-1-dev
sudo apt --fix-broken install
mailspring 
# Thunderbird
# evolution
```
## full screen shortcut 
```
gnome-terminal --window --full-screen
```

## installing Ghidra
```
su -

echo "deb http://ppa.launchpad.net/linuxuprising/java/ubuntu focal main" | tee /etc/apt/sources.list.d/linuxuprising-java.list

apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 73C3DB2A

apt-get update

apt-get install oracle-java11-installer-local

exit
https://www.linuxuprising.com/2019/06/new-oracle-java-11-installer-for-ubuntu.html
https://askubuntu.com/questions/1175624/how-can-i-remove-the-package-oracle-java11-installer-local
```


## installing Discord
```
sudo dpkg -i discord-0.0.12.deb
sudo apt install libappindicator1
sudo apt --fix-broken install
```

##  installing spotify
```
# spotify
wget http://repository.spotify.com/pool/non-free/s/spotify-client/spotify-client_1.1.42.622.gbd112320-37_amd64.deb
sudo dpkg -i xxx.deb

# adblock 
git clone https://github.com/abba23/spotify-adblock-linux.git
cd spotify-adblock-linux
wget -O cef.tar.bz2 http://opensource.spotify.com/cefbuilds/cef_binary_80.0.8%2Bgf96cd1d%2Bchromium-80.0.3987.132_linux64_minimal.tar.bz2
tar -xf cef.tar.bz2 --wildcards '*/include' --strip-components=1
make
sudo make install

# start 
LD_PRELOAD=/usr/local/lib/spotify-adblock.so spotify
```

