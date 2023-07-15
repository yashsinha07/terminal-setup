# terminal-setup
This repository contains the configuration for my terminal and vim environment.


brew install starship

Plugins to be installed:

**homebrew**: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

**starship theme**: `brew install sharship` 

**fonts**: 
    `brew tap homebrew/cask-fonts`
    `brew install --cask font-hack-nerd-font`

**zsh-auto-suggestions**: `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`

**zsh-syntax-highlighting**: `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`

**cmatrix** screensaver: `brew install cmatrix`

**figlet**: `brew install figlet`

After installing the plugins, run the applyConfig.sh script by `<path_to_>/terminal-setup/applyConfig.sh` in your terminal.

Happy Coding! :)
