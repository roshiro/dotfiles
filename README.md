My Dotfiles
===========

A place to store my dot files for coding

Usage
-----

Clone into ~/dotfiles/

Then add symlinks in your ~/ directory

Symlink vim:
  ln -nfs ~/dotfiles/ .vim

Symlink .vimrc:
  ln -nfs ~/dotfiles/vimrc .vimrc

Symlink .gvimrc:
  ln -nfs ~/dotfiles/gvimrc .gvimrc

Symlink .bash_aliases
  ln -nfs ~/dotfiles/bash_aliases .bash_aliases

Symlink .gitconfig
  ln -nfs ~/dotfiles/gitconfig .gitconfig

Symlink .gitignore
  ln -nfs ~/dotfiles/gitignore .gitignore

Symlink .gemrc
  ln -nfs ~/dotfiles/gemrc .gemrc


Enabling Git Auto-Completion
-----

add the following line to `~/.bash_profile`
`source ~/dotfiles/.git-completion.sh`