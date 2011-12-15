# dotvim

This is my vim config. It kinda sucks, but feel free to use it. It uses
pathogen, so to install it, run the following commands.

```
git clone git://github.com/Anadol/dotvim.git .vim
cd .vim
git submodule init
git submodule update
ln -s vimrc ../.vimrc
ln -s gvimrc ../.gvimrc
cd bundle/command-t
rake make # requires ruby
```
