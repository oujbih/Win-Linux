- pkill -f tmux
# tmux set -g mouse-mode on doesn't work
```
# Make mouse useful in copy mode
set -g mouse on
```

## tmux: hangs and do not load, and do not respond to any option command 
```
deleting /tmp/tmux-NNNNNNN
```
## alias 
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
