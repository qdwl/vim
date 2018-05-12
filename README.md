# vim
（1）将.vimrc放到$HOME目录下
（2）安装vundle
    $ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    默认安装在/.vim/bundle/vundle下；
（3）执行vim，然后执行PluginInstall 自动下载安装插件
（4）YouComplete编译安装
    python-dev安装：
    ubuntu：sudo apt-get install python2.7-dev

    YouCompleteMe 安装：
    python install.py --clang-completer
