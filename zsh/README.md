# install zsh
```bash
sudo apt install zsh
sudo chsh -s /bin/zsh john
```

# install and configure oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

install plugins:
```
zsh ~/.config/install-plugins
```

enable plugins:
```bash
plugins=(
  git
  zsh-autosuggestions
  zsh-syntax-highlighting
)
```

zsh theme:
```
ZSH_THEME="crcandy"
```

# configure with my config

```
cd ~
git clone https://github.com/Thespica/.config.git
```

