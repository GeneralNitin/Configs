## Mac Things

### Setting up oh my zsh:
1. Install: Go to the below website
```
https://ohmyz.sh/#install
```

2. Follow this video for the config
```
https://www.youtube.com/watch?v=9eJ0HHHNuls
```

3. Few commands for helping:
  - `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`
  - `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`
  - `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`

4. .zshrc examples:
```
...
ZSH_THEME="powerlevel10k/powerlevel10k"
...
plugins=(
  git
  zsh-autosuggestions
  zsh-syntax-highlighting
  )
```

5. Install font: [Download font](./oh-my-zsh/SourceCodePro+Powerline+Awesome+Regular.ttf)

7. Configure theme using
```
p10k configure
```
