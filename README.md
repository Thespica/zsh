# install zsh for user

```bash
sudo apt install zsh
sudo chsh -s /bin/zsh <user-name>
```

# install and configure oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

# configure with my config

```
cd ~/.config
git clone https://github.com/Thespica/zsh.git
echo "source ~/.config/zsh/zshrc" >> ~/.zshrc
```

install plugins:
```
zsh ~/.config/zsh/install-plugins.zsh
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

