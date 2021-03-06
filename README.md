# My development aliases

### For macOs

:bulb: which default shell?

```sh
echo $SHELL
// /bin/zsh
nano .zprofile
// /bin/bash
nano .bash_profile
```
___
```
alias pg='ping google.com'
alias b='brew'
alias ll='ls -alGF'
alias g='git'
alias d='docker'
alias dc='docker-compose'
alias v='vagrant'
alias h='history | grep'
alias n='npm'
alias gpom='git pull origin master'
alias gcm='git checkout master'
alias grm='git rebase master'
alias odoc='open ~/Documents'
alias odl='open ~/Downloads'
alias ghnr='open -a /Applications/Google\ Chrome.app/ https://github.com/new'
alias ip='ifconfig en0 |grep "inet "'
alias sub='/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl'
alias y='yarn'
alias k=kubectl
```


### For Ubuntu

```
alias pg='ping google.com'
alias g='git'
alias d='docker'
alias dc='docker-compose'
alias v='vagrant'
alias h='history | grep'
alias n='npm'
alias gpom='git pull origin master'
alias gcm='git checkout master'
alias grm='git rebase master'
alias odoc='open ~/Documents'
alias odl='open ~/Downloads'
alias ip='ifconfig en0 |grep "inet "'
alias y='yarn'
alias fixupdate='sudo rm /var/lib/apt/lists/lock && sudo rm /var/cache/apt/archives/lock && sudo rm /var/lib/dpkg/lock'
```

### git config --global -l

```
alias.co=checkout
alias.b=branch
alias.s=status
alias.c=commit
alias.m=merge
alias.p=push
alias.r=rebase
alias.l=log
alias.cp=cherry-pick
alias.a=add
alias.d=diff
alias.f=fetch
```
