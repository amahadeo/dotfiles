# dotfiles

```
After cloning to home directory...
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
ln -s ~/dotfiles/vimrc ~/.vimrc 
npm -g install instant-markdown-d

In Vim...
:PlugInstall
:GoInstallBinaries

Back In Terminal for YCM...
sudo apt install build-essential cmake python3-dev
cd ~/.vim/plugged/youcompleteme
python3 install.py --go-completer --ts-completer
```
