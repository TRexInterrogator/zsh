# ZSH Setup
Autosuggest + syntax highlighting + git status

```.sh
brew install zsh-autosuggestions
brew install zsh-syntax-highlighting
```

Add to `~/.zshrc`

```.sh
source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh
source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

Reload shell with `source ~/.zshrc`