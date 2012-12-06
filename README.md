# dotvim

This is my vim config. It kinda sucks, but feel free to use it. It uses
pathogen, so to install it, run the following commands.

```
git clone git://github.com/rstarosta/dotvim.git .vim
cd .vim
git submodule init
git submodule update
cd ..
ln -s .vim/vimrc .vimrc
ln -s .vim/gvimrc .gvimrc
cd .vim/bundle/command-t
rake make # requires ruby
```
