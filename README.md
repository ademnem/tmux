# Tmux Configuration
This config corrects colors in neovim and adds custom key binds.

**STEPS:** 
1. Clone this repo to $HOME/.config/
2. Add this to .bashrc
```
# TMUX
export TMUX_CONF=$HOME/.config/tmux/tmux.conf
if [ -n "$TMUX" ]; then
    tmux source-file 
fi
```
