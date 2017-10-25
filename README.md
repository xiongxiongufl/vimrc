# vimrc

This repo stores the configuration of my vim editor.

1. Set up Vundle:

```bash
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

2. Get Pathogen
```bash
$ curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

3. Clone .vimrc

```bash
$ wget https://raw.githubusercontent.com/xiongxiongufl/vimrc/master/.vimrc ~/
```

4. Install plugins

```vim
:PluginInstall
```

## Issues

If vim cannot register system clipboard, try reinstalling vim with gtk.

```bash
$ sudo apt-get install vim-gtk
```
