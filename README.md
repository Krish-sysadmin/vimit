# vimit
Vim config


If .vim and .vimrc exist and you want to back them up:

```
mkdir $HOME/backupofvimconfigs 
sudo mv  $HOME/.vim $HOME/.vimrc $HOME/backupofvimconfigs 
```

If you want to delete them:

```
sudo rm -rf $HOME/.vimrc $HOME/.vim/
```

Then

```
git clone  https://github.com/Krish-sysadmin/vimit/ vim-config  &&  sudo mv  vim-config/.vim vim-config/.vimrc $HOME/   && sudo git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim   && vim +PluginInstall +qall
```
  


<img width="1792" alt="Screenshot 2021-10-24 at 9 13 14 pm" src="https://user-images.githubusercontent.com/75043245/138609155-0962ddde-5961-40cd-8cda-5f8da4cfd485.png">
