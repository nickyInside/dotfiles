dotfiles
========

These are mine :)


This repository contains some configuration files.

#Installation

    git clone git@github.com:nickyInside/dotfiles.git
    
    
## Git
For Git configuration and global ignore files, create these symlinks:

    $ ln -s ~/.dotfiles/git/gitconfig ~/.gitconfig
    $ ln -s ~/.dotfiles/git/gitignore_global ~/.gitignore_global
    $ ln -s ~/.dotfiles/git/gitkrc ~/.gitkrc
    
## Ruby
In order to prevent `gem install` or `gem update` from downloading RDoc and RI, symlink this file.

    $ ln -s ~/.dotfiles/ruby/gemrc ~/.gemrc
	
## Vim
For Vim configuration and use, create the following symlinks:

    ln -s ~/.dotfiles/vim ~/.vim
    ln -s ~/.dotfiles/vim/vimrc ~/.vimrc

## tmux (terminal multiplexer) configuration
For tmux configuration create this symlink:

    $ ln -s ~/.dotfiles/tmux/tmux_conf ~/.tmux_conf

## Sublime Text 2 (subl)
Add this symlink:

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    $ ln -s ~/.dotfiles/sublime/User User

## Doing
Install `doing` gem

    $ [sudo] gem install doing

Create symlink to `doingrc` file.

    $ ln -s ~/.dotfiles/doing/doingrc ~/.doingrc




