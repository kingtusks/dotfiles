# dotfiles

My Neovim (LazyVim) and tmux configuration.

## Contents

- `nvim/` — Neovim config (LazyVim-based)
- `.tmux.conf` — tmux config
- `.gitignore`

## Setup

```bash
# Neovim
git clone git@github.com:kingtusks/dotfiles.git ~/.config/dotfiles
ln -s ~/.config/dotfiles/nvim ~/.config/nvim

# tmux
ln -s ~/.config/dotfiles/.tmux.conf ~/.tmux.conf
```

Then launch `nvim` and let Lazy install the plugins.
