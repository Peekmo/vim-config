```
git submodule update --init --recursive
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
cd ~/ && ln -s ~/.vim/.vimrc
cd ~/.vim/bundle/YouCompleteMe && ./install.py
```
