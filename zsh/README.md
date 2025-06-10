# Setting up ZSH
## Install ZSH
1. Run `sudo apt-get update && sudo apt-get upgrade` in the terminal prior to running any installation scripts.
2. Run `sudo apt install zsh` in the terminal. Confirm it has been installed correctly by running `zsh --version`
3. Change the default shell from Bash to ZSH by running chsh -s $(which zsh) and restart the PC to make sure the change takes.
## Install oh-my-zsh
Copy and run the following curl script in your terminal. If the installation is a success, you will see a colourful message telling you oh my zsh is now installed.
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
### Install the powerlevel9k oh-my-zsh theme
1. CLone the repo directly into the `.oh-my-zsh` custom themes folder with this command: 
```
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
```
2. Replace the `.zshrc` file with the one in this repository's folder.
3. You will also need to download and install the Powerline fonts as per the documentation in the [powerlevel9k repo](https://github.com/Powerlevel9k/powerlevel9k/wiki/Install-Instructions#step-2-install-a-powerline-font).