# Setup iterm2 + powerlevel10k theme + ssh for mac os


### Install iterm2:

https://iterm2.com

### Install oh-my-zsh:

https://ohmyz.sh

### Install powerlevel10k :

https://github.com/romkatv/powerlevel10k

after setup powerlevel10k copy all the line of the .p10k.zsh in the repository to the ~/.p10k.zsh file create in the computer

### PLUGINS

=> zsh-autosuggestions :

Show the last command

https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh

=> zsh-syntax-highlighting:

Color the command 

https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md

### command 

**file configuration oh my zsh**
code ~/.zshrc 

**file configuration of powerlevel10k**
code ~/.p10k.zsh

use code for open with vscode or use nano editor

## Manually generating your SSH key in macOS

follow the instruction and type enter for passphrase (no setup a passphrase)

ssh-keygen -t rsa 

Check if the keys exist 

ls ~/.ssh

Save key to the clipboard(change the **_id_rsa.pub_** by the right key in the computer)

pbcopy < ~/.ssh/id_rsa.pub

More infos :

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh
