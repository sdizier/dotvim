# Installation

      git clone git://github.com/sdizier/dotvim.git ~/.vim

Create symlinks
	
  	ln -s ~/.vim/vimrc ~/.vimrc

Switch to the ~/.vim directory and fetch submodules

  	cd ~/.vim
  	git submodule init
  	git submodule update
  	
Install Ack

	sudo apt-get install ack-grep
	
Softlink ack

	sudo ln -s /usr/bin/ack-grep /usr/bin/ack

## Command-T

Compile command-t

    cd bundle/command-t
    rvm use system # Need to compile with Ruby 1.8
    rake make

## Molokai

For the molokai color scheme

    sudo apt-get install ncurses-term

Add to .bashrc:
    
    export TERM=xterm-256color

## JSHint

For jshint, install npm

    sudo apt-get install npm -y
    npm install jshint
