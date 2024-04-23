## Prerequisites

- oh-my-zsh
- zsh

Set source `~/.zshrc` to `source ~/.config/zsh`

## Plugins

To install plugins, they need to be pulled locally first, and then extended in `~/.config/.zshrc` plugins

### Example

- git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
- edit ~/.config/.zshrc plugins property to include `plugins=(git zsh-autosuggestions)`

- fzf - can be installed via `brew` `brew install fzf`
- (zsh-syntax-highlighting)[https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting]
- (zsh-autosuggestions)[https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions]
- (zsh-fast-syntax-highlighting)[https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting]
