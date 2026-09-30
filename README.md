# dotfiles

My personal configuration files, gathered here from what used to be separate
repos (`vim-config`, `tmux-config`, ...) so they're easier to keep in sync
and share.

## Structure

| Directory | Contents | Install |
|---|---|---|
| [`vim/`](./vim) | Vim configuration | `cp vim/vimrc ~/.vimrc` |
| [`tmux/`](./tmux) | Tmux configuration | `cp tmux/tmux.conf ~/.tmux.conf` |

Each directory has its own README with more details and links.

## Installation

Clone the repo and symlink (or copy) the files you want into place:

```
git clone git@github.com:johaab/dotfiles.git
cd dotfiles
ln -sf "$(pwd)/vim/vimrc" ~/.vimrc
ln -sf "$(pwd)/tmux/tmux.conf" ~/.tmux.conf
```
