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
alias android='bash /usr/local/android-studio/bin/studio.sh'
#https://www.cyberciti.biz/tips/bash-aliases-mac-centos-linux-unix.html
https://thoughtbot.com/blog/a-tmux-crash-course ## very good

```
## tmux not displaying bash prompt colors
```
code ~/.tmux.conf
set-option -g default-command bash
```
## copy paste 
```
# List of plugins
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-sensible'
set -g @plugin 'tmux-plugins/tmux-yank'

# Other examples:
# set -g @plugin 'github_username/plugin_name'
# set -g @plugin 'git@github.com:user/plugin'
# set -g @plugin 'git@bitbucket.com:user/plugin'

# Initialize TMUX plugin manager (keep this line at the very bottom of tmux.conf)
run '~/.tmux/plugins/tpm/tpm'

To use the copy and paste using tmux-yank you need to:
- Highlight the text with your mouse cursor
- Press y
- Paste to wherever you want

Download tmux here: https://github.com/tmux/tmux/wiki
Download tmux plugin manager here: https://github.com/tmux-plugins/tpm
Download tmux-yank here: https://github.com/tmux-plugins/tmux-...

```
