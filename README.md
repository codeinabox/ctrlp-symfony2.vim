# ctrlp-symfony2.vim

This is a ctrlp.vim extension that allows you to open your Symfony2 app files easily. Works only in Unix-like operating systems. For now, this plugin provides:

* `:CtrlPSymfony2Entities` list all project entities and their mapping files
* `:CtrlPSymfony2Controllers` list all project controllers
* `:CtrlPSymfony2Views` list all project views
* `:CtrlPSymfony2Assets` list all project assets files
* `:CtrlPSymfony2Configs` list all project config files exept entities mapping files

## Installation

### Using [pathogen](https://github.com/tpope/vim-pathogen)

``` sh
git clone git://github.com/voronkovich/ctrlp-symfony2.vim ~/.vim/bundle/ctrlp-symfony2.vim
```

### Using [vundle](https://github.com/gmarik/vundle)

Add to vimrc:

``` vim
Plugin 'voronkovich/ctrlp-symfony2.vim'
```

### Running tests


Tests are run using a Ruby test runner, so you'll have to have Ruby installed, then run

```sh
$ gem install vim-flavor
```

Now you can run tests with

```sh
$ vim-flavor test spec/
```

## License

Copyright (c) Voronkovich Oleg.  Distributed under the same terms as Vim itself.
See `:help license`.
