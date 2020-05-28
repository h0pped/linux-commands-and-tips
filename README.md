# Arch Linux tips

Some useful tips for yourself and for beginners in Linux world

# Disable webcam 
You just need to disable all permissions for the file /dev/video0
```sh
 - cd /dev
 - chmod 000 video0
```
  

# Install packages from AUR
```sh
 - clone it (git clone)
 - inside of the cloned folder
 - makepkg -si
```
  
  
# Terminal customization
   I use figlet(ascii art) + lolcat(rainbow text) + archey3(PC specs). /etc/bash.bashrc saves commands executed when opening the terminal
   ```sh
 - clear
 - figlet -f slant "TEXT" | lolcat 
   ````
  To make custom prompt you need to edit PS1 inside of .bashrc file (bash.bashrc and .bashrc are different files!)
```sh
 - PS1="$(tput setaf 10)\u"
 - PS1+="$(tput setaf 118)@\h "
 - PS1+="\W -> "
 - PS1+="$(tput sgr0)";
   ````
  
 
#### _This is a personal list of commands (so as not to forget something important xd), it will be replenished as needed_
