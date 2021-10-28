## Fix apt 
```
sudo add-apt-repository --remove http://ppa.launchpad.net/webupd8team/java/ubuntu
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
