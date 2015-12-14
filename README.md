# my_vimrc

mkdir ~/.vim/autoload
cd ~/.vim/autoload
wget https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

cd ~
wget -O ~/.vimrc https://raw.githubusercontent.com/39386078/my_vimrc/master/vimrc.txt 


#run Following command in your vim

:plugInstall

#YouCompleteMe

:!~/.vim/plugged/YouCompleteMe/install.py --clang-completer --system-libclang --omnisharp-completer --gocode-completer

:!cp ~/.vim/plugged/YouCompleteMe/third_party/ycmd/examples/.ycm_extra_conf.py ~/
