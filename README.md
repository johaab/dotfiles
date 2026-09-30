# dotfiles

My personal configuration files.

## Contents

- `.vimrc` — Vim configuration
- `.tmux.conf` — Tmux configuration

## Installation

Clone the repo and symlink the files you want into place:

```
git clone git@github.com:johaab/dotfiles.git
cd dotfiles
ln -sf "$(pwd)/.vimrc" ~/.vimrc
ln -sf "$(pwd)/.tmux.conf" ~/.tmux.conf
```

## Tmux + iTerm2

If you use iTerm2, go to iTerm2 > Settings > Profiles > Keys and set
"Left Option key" to "Esc+" so tmux keybindings work as expected.

## Links

- [Vim Cheat Sheet](https://vim.rtorr.com/)
- [Missing Semester: Editors](https://missing.csail.mit.edu/2020/editors/)
- [Tmux Cheat Sheet](https://tmuxcheatsheet.com/)
- [A guide to customizing your tmux.conf](https://hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)
