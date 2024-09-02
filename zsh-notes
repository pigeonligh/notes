# ZSH

## Oh-my-zsh

### install
```
sh -c "$(curl -fsSL https://gitee.com/leok77s/ohmyzsh-gitee/raw/main/install.gitee.sh)"
```

### zshrc
```
# zsh
export ZSH="$HOME/.oh-my-zsh"
ZSH_THEME="ys"
plugins=(git)

source $ZSH/oh-my-zsh.sh

# Download Znap, if it's not there yet.
[[ -r ~/Repos/znap/znap.zsh ]] ||
    git clone --depth 1 -- \
        https://gh-proxy.com/https://github.com/marlonrichert/zsh-snap.git ~/Repos/znap
source ~/Repos/znap/znap.zsh  # Start Znap

# zsh plugins
znap clone https://gh-proxy.com/https://github.com/zsh-users/zsh-completions.git
znap clone https://gh-proxy.com/https://github.com/zsh-users/zsh-autosuggestions.git
znap clone https://gh-proxy.com/https://github.com/zsh-users/zsh-syntax-highlighting.git
znap clone https://gh-proxy.com/https://github.com/zsh-users/zsh-history-substring-search.git
znap source zsh-users/zsh-completions
znap source zsh-users/zsh-autosuggestions
znap source zsh-users/zsh-syntax-highlighting
znap source zsh-users/zsh-history-substring-search

# Golang
export PATH=$PATH:/usr/local/go/bin
```
