# vim 8 installation

```
sudo add-apt-repository ppa:jonathonf/vim
sudo apt update
sudo apt install vim
```

# vimrc
My vimrc

Installation

```
$ cd
$ mv .vimrc .vimrcbak
$ ln -s .vim/vimrc .vimrc
```
# Working

VIM using plugins PATHOGEN to load automatically all plugins

# Plugins

[Nerdtree](https://github.com/scrooloose/nerdtree) (:NERDTreeToggle) : file manager for VIM.
you can made some operation (copy cut past etc) with key 'm'

[Fugitive](https://github.com/tpope/vim-fugitive) : GIT wrapper

[Nextval](https://github.com/vim-scripts/nextval) : use CTRL+a to increment a value or a change a boolean (from true to false to true etc)

[Tabular](https://github.com/godlygeek/tabular) : useful to line up text

[Colorizer](https://github.com/vim-scripts/colorizer) : colorize the color code starting with #FFFFFF

# keybinding

:VimGameCodeBreak > boring code

```
ctrl+a > increment a value or a change a boolean (from true to false to true etc)

:Tab /=       > align text to '='
:Tab /:\zs    > align text to ':' but exclude the ':' character
gg            > end of line
cw            > replace word
$             > go to end of line
a             > go to begining of the line

:set list : show hidden character (tabulation, space, end of line ...)

split windows:

```
