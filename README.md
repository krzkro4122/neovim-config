# My neovim config

## Includes:
 - Dracula theme
 - File navigation tree
 - Code completion and diagnostics (VScode COC engine)
 - Integrated terminal

![image](https://user-images.githubusercontent.com/75375838/178107994-784b6786-43e9-4630-8391-fbc4c324f588.png)


-----

## Installation

Make a nvim config dir and put the `init.vim` file inside
```
mkdir ~/.config/nvim
cp init.vim ~/.config/nvim
```
Enable nvim plugins
```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
Install the plugins listed in `init.vim`
```
nvim +PlugInstall
```
