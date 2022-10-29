#Documentation of Course

This is the documentation for my 'Baumeisterkurs'. It should primarily test the functions of my remote github repository

Setup Latex on mac.

1. Install Vim

2. Create .vimrc
  set nocompatible

  filetype on

  filetype plugin on

  filetype indent on

  syntax on

  set shellslash
3. Plugins for vim
mkdir -p ~/.vim/autoload ~/.vim/bundle

curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

Add the following lines to .vimrc
  execute pathogen#infect()
  syntax on
  filetype plugin indent on

  ...
  <the rest of the file>
  ...
  
  4. Download vim-latex-plugin and copy into .vim or .vimfiles and extract there
  
    tar -xvf vim-latex-10.1....
    
