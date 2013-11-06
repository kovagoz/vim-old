vim
===

This is my Vim configuration.

## Requirements

[Powerline fonts](https://github.com/Lokaltog/powerline-fonts) have installed on your host.

You need vim compiled with Python 2.6+ or 3.2+ support for Powerline to work (vim-nox package on Debian).

## Installation

```bash
git clone https://github.com/kovagoz/vim ~/.vim --recursive
echo 'source ~/.vim/vimrc' > ~/.vimrc
vim +BundleInstall +qall
```
