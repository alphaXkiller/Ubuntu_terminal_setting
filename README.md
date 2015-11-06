# Ubuntu_terminal_setting

## You will need to modify ~/.bashrc file. If there is none, please create one by: touch .bashrc

PS variables: (http://www.thegeekstuff.com/2008/09/bash-shell-ps1-10-examples-to-make-your-linux-prompt-like-angelina-jolie/)
* PS1:  \u - Username
      \h - Hostname
      \w - Current directory
      
* PS2: Current time in the promt
* PS3: Linux command
* PS4: Foreground color of promt

### Color setting for username, host and directory
example:
* Uncomment force_color_promt=yes, so that you can change the color
* PS1="\[\e[34m\]\u@\[\e[31m\]\h:\[\e[35m\]\w/ \[\e[0m\]\$\[\e[37m\] "
