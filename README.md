# simplzshell  
## Simple but Elegant
Explore a minimalist and elegant oh-my-zsh theme I've created, focusing on simplicity with a touch of sophistication. Elevate your terminal experience with style.


![image](https://github.com/MrNeoTr1n0/simplzshell/assets/149966763/d419ebb8-c2b7-40dd-a43c-4f4998b1c361)


## Installation
For the Regular User:
Run this command as the regular user to download the simplzshelluser.zsh-theme and place it in the user's custom themes directory.
```
curl -fsSL https://raw.githubusercontent.com/0xAb1d/simplzshell/main/simplzshelluser.zsh-theme -o ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/simplzshelluser.zsh-theme
```

For the Root User:
Run this command as the root user (`sudo -i` first if needed) to download the simplzshellroot.zsh-theme and place it in the root’s custom themes directory.
```
curl -fsSL https://raw.githubusercontent.com/0xAb1d/simplzshell/main/simplzshellroot.zsh-theme -o ${ZSH_CUSTOM:-/root/.oh-my-zsh/custom}/themes/simplzshellroot.zsh-theme
```


for user:
```
ZSH_THEME="simplzshelluser"
```
for root:
```
ZSH_THEME="simplzshellroot"
```
Reload:
```
source /root/.zshrc
```
