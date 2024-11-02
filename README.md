Need to install (install.sh)
```
sudo apt-get install curl
sudo apt-get install nodejs
sudo apt-get install npm
sudo apt-get install clangd

curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

And enter some commands in vim
```
:PlugInstall
:CocInstall coc-cmake
:w
:source %
```
