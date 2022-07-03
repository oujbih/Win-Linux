## Fix apt 
```
sudo add-apt-repository --remove http://ppa.launchpad.net/webupd8team/java/ubuntu
```

## Create bootable USB 
```
sudo dd bs=4M if=/home/gtc/Documents/GTC/PC/ubuntu-20.04.3-desktop-amd64.iso of=/dev/sda1 status=progress oflag=sync
https://vitux.com/ubuntu-bootable-usb-stick/
```




## Watch
```
watch -n 0.5 -d ls -la
```

## Transfer file windows ---> linux
```
win    : C:\xampp\htdocs\gym\upload\nc.exe 10.10.15.130 5555 < CloudMe_1112.exe
linux  : nc -nlvp 5555 > CloudMe_1112.exe
```

## Find public ip
```
dig +short myip.opendns.com @resolver1.opendns.com
```
## how to find large files on linux
```
find -type f -exec du -Sh {} + | sort -rh | head -n 5

ss -lptn | grep 8881
sudo netstat -plunt |grep postgres
```

##   network-manager 
```
service network-manager restart
```
## crontab run every 15 minutes between certain hours
```
*/15 7-19 * * * /path/script >/dev/null 2>&1
```
