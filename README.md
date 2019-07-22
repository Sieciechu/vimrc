# vimrc
Here is my .vimrc file. It uses Vim Vundle plugin manager - https://github.com/VundleVim/Vundle.vim .

make.sh - shell script which will link myvimrc to ~/.vimrc

### Installation
In console run

`$ git clone git@github.com:Sieciechu/vimrc.git ~/.vim && git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim && cd ~/.vim && ./make.sh && vim myvimrc -c "source %" -c "PluginInstall"`

**Warning** Above command clones repo to ~/.vim, so if you have already something there, be sure to make backup before cloning.

### Other
For Vim Vundle doc you may check https://github.com/VundleVim/Vundle.vim

For other vim plugins you may check https://vimawesome.com/

