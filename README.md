# vimrc

This repo stores the configuration of my vim editor.

1. Set up Vundle:

```bash
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

2. Clone .vimrc

```bash
$ wget https://raw.githubusercontent.com/xiongxiongufl/vimrc/master/.vimrc ~/
```

3. Install plugins

```vim
:PluginList       - lists configured plugins
:PluginInstall    - installs plugins; append `!` to update or just :PluginUpdate
:PluginSearch foo - searches for foo; append `!` to refresh local cache
:PluginClean      - confirms removal of unused plugins; append `!` to auto-approve removal
```

## Issues

If vim cannot register system clipboard, try reinstalling vim with gtk.

```bash
$ sudo apt-get install vim-gtk
```
