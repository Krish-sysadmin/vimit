# vimit
Vim config


If .vim and .vimrc exist and you want to back them up:

```
mkdir $HOME/backupofvimconfigs 
sudo mv  vim-config/.vim vim-config/.vimrc $HOME/
```

If you want to delete them:

```
sudo rm -rf $HOME/.vimrc $HOME/.vim/
```

Then

```
git clone  https://github.com/Krish-sysadmin/vimit/ vim-config  &&  sudo mv  vim-config/.vim vim-config/.vimrc $HOME/   && sudo git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim   && vim +PluginInstall +qall
```
  
