# Minimalistic zsh config

This is my basic config for working in shell with minimal aliases, and plugins, consists of:

- autocompletion
- syntax-highlighting
- fzf

## Prerequisites

- oh-my-zsh
- zsh

## Setup

- Clone this repo to `~/.config/zsh`
- Get all plugins locally (fzf via brew, rest can be via git clone)
- Set source in `~/.zshrc` to `source ~/.config/zsh`

## Plugins

To install plugins, they need to be pulled locally first, and then extended in `~/.config/.zshrc` plugins

### Example install

```sh
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions

- edit ~/.config/.zshrc plugins property to include `plugins=(git zsh-autosuggestions)`
```

### Plugins list

- fzf - can be installed via `brew` `brew install fzf`
- (zsh-syntax-highlighting)[https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting]
- (zsh-autosuggestions)[https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions]
- (zsh-fast-syntax-highlighting)[https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting]
- (zsh-nvm)[https://github.com/lukechilds/zsh-nvm ~/.oh-my-zsh/custom/plugins/zsh-nvm]
