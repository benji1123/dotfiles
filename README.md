### Tools
- [**iTerm2**](https://iterm2.com/index.html) (term)
- [**Starship**](https://starship.rs/) (prompt)
- [**Fira Code**](https://www.nerdfonts.com/font-downloads) (nerd font)
- [**neovim**](https://neovim.io/)
- [**nvchad**](https://nvchad.com/)

### .zshrc

```
alias zsh="nvim ~/.zshrc"

# https://www.imagemagick.org/script/mogrify.php
alias shrink50="magick mogrify -resize 50% *.jpg"
alias tojpg="magick mogrify -format jpg *.png"
```

### git
```
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
```
