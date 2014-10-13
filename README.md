Vimsetup
==========

My Vim setup.

## Installation

### Fedora / RedHat / CentOS

```sh
sudo yum install vim gvim
sudo yum install ctags-etags ncurses-term xsel
curl -L https://github.com/hbin/top-programming-fonts/raw/master/install.sh | bash
git clone https://github.com/aleknak/vimsetup.git ~/.vim
cd ~/.vim
git submodule update --init
echo "source ~/.vim/vimrc" > ~/.vimrc
```
### Ubuntu

```sh
sudo apt-get install vim-gnome
sudo apt-get install exuberant-ctags ncurses-term xsel
curl -L https://github.com/hbin/top-programming-fonts/raw/master/install.sh | bash
git clone https://github.com/aleknak/vimsetup.git ~/.vim
cd ~/.vim
git submodule update --init
echo "source ~/.vim/vimrc" > ~/.vimrc
```
## Update

```sh
cd ~/.vim
git pull origin master

# Update submodules
git submodule update --init
git submodule sync
git submodule foreach git pull origin master
```

## Plugins

* https://github.com/tpope/vim-pathogen
* https://github.com/tpope/vim-rails
* https://github.com/tpope/vim-rake
* https://github.com/tpope/vim-bundler
* https://github.com/tpope/vim-fugitive
* https://github.com/tpope/vim-haml
* https://github.com/tpope/vim-surround
* https://github.com/tpope/vim-endwise
* https://github.com/tpope/vim-commentary
* https://github.com/tpope/vim-cucumber
* https://github.com/tpope/vim-markdown
* https://github.com/scrooloose/nerdtree
* https://github.com/corntrace/bufexplorer
* https://github.com/ervandew/supertab
* https://github.com/dalibor/snipmate.vim
* https://github.com/dalibor/snipmate-snippets
* https://github.com/vim-ruby/vim-ruby
* https://github.com/mileszs/ack.vim
* https://github.com/kchmck/vim-coffee-script.git
* https://github.com/tsaleh/vim-matchit.git
* https://github.com/kien/ctrlp.vim
* https://github.com/benmills/vimux
* https://github.com/skalnik/vim-vroom
* https://github.com/Lokaltog/vim-easymotion
* https://github.com/tpope/vim-ragtag
* https://github.com/pangloss/vim-javascript
* https://github.com/othree/javascript-libraries-syntax.vim
* https://github.com/godlygeek/tabular

## Themes
* https://github.com/ChrisKempson/Tomorrow-Theme
* https://github.com/altercation/vim-colors-solarized.git

## Fonts
* https://github.com/hbin/top-programming-fonts

Acknowledgements
----------------
A HUGE thank you is owed to [Dalibor Nasevic], for putting together a great Ruby on Rails setup. This setup is totally inspired by [vimfiles].

Version
----
1.0

License
-----------
[Beerware License]

[Beerware License]:http://en.wikipedia.org/wiki/Beerware
[Dalibor Nasevic]:https://github.com/dalibor
[vimfiles]:https://github.com/dalibor/vimfiles
