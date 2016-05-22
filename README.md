```
git submodule update --init --recursive
cd ~/ && ln -s ~/.vim/.vimrc
cd ~/.vim/bundle/YouCompleteMe && ./install.py
cd ~/.vim/bundle/vimproc.vim && make
cd ~/.vim/bundle/command-t/ruby/command-t && ruby extconf.rb && make
```

Pour vim-go executer `:GoUpdateBinaries` dans vim
