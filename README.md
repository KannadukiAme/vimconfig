# Vimconfig

> vim config

## Plug

list:
- posva/vim-vue

## Custom

color:
- darkrobot

editor:
- line number

## Usage

install vim-plug

Unix/Linux
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

copy .vimrc to ~/.vimrc 
copy color to ~/.vim/color
```
git clone GIT_URL
```

don't forget to install vim-plug's plugins.
```
:PlugInstall
```

install YCM

install complier tools for Ubuntu18.04 and later

```
sudo apt install build-essential cmake python3-dev
```

```
python3 install.py --tern-completer
```