vim-config
==========

Vim's config. WIP.

Steps to install dotfiles:

1. Clone the repo ``cd ~ && git clone git@github.com:lukaszklis/vim-config.git``
2. Create symlinks for vim’s files: ``ln -s ~/vim-config/vim ~/.vim && ln -s ~/vim-config/vimrc ~/.vimrc``
3. Install Vundle: ``git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle``
4. Install bundles: ``vim ~/.vimrc``. Enter the following in Vim: ``:BundleInstall``
5. Enjoy! :)
