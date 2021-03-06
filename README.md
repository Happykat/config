# My dotfiles

## Content

 * neovim configuration : init.vim
 * tmux configuration   : .tmux.conf
 * zsh configuration    : .zshrc
 * tilda configuratin   : config_0


## Depencencies

 * [Neovim](https://github.com/neovim/neovim)
 * tmux
 * zsh
 * [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
 * [bullet-train for oh-my-zsh](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme)

## Install

### Clone this repo 

```sh
$ git clone git@github.com:Happykat/Dotfiles.git
```

### Copy the files

```sh
$ cp .tmux.conf ~
```

```sh
$ cp init.vim $XDG_CONFIG_HOME/nvim
```

**$XDG_CONFIG_HOME might not be set for you , it default to /home/.config**

```sh
$ mkdir ~/.config/nvim/undodir
```

```sh
$ cp .zshrc ~
```

### Zsh

**edit the .zshrc to change the home directory according to yours.**

``` "(YOUR_HOME)" becomes your actual home ```


## Influences

My init.vim is LARGELY based on [mhartington's](https://github.com/mhartington)

You will find in his repos , some awesomes dotfiles , neovim themes etc...

Most of the credits for the neovim config goes to him.

## Result

## Terminal

Screenshot taken under Guake terminal , with Monokai theme

![Alt text](img/terminal.png?raw=true "Title")

## [Neovim](https://github.com/neovim/neovim)

The current theme is : [FlatColor by MaxSt](https://github.com/MaxSt/FlatColor)

Whith some tweaks on NERDTree , see the section themes in init.vim for more informations

![Alt text](img/neovim.png?raw=true "Title")
