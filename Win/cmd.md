
## directory
```Windows command     Unix command
rmdir               rmdir
rmdir /s            rm -r
move                mv
```

## How to Format USB
```
diskpart 
list disk
select disk 2
clean
create partition primary
format fs=ntfs
assign 
```

## get ip of website
```
tracert + the URL
```
