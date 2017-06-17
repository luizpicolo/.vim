# Vim Configurations

My .vim dotfiles and configurations. 	

## Install

Just run the following commands via terminal to get perfectly set up:

    $ cd ~/
    $ rm -rf .vim && .vimrc    
    $ git clone https://github.com/luizpicolo/vim.git vim
    $ ln -sf ~/vim/.vimrc ~/.vimrc
    $ ln -sf ~/vim/.vim ~/.vim   
    $ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

## Update

    $ cd ~/vim    
    $ git pull origin master

## Dependences

 - [Ack](https://beyondgrep.com/install/)
 - [Vundle](https://github.com/VundleVim/Vundle.vim.git)
