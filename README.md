VIM-sac plugin
==============

This repository provides a VIM syntax file for the SaC programming language. The
syntax file is provided as
[Pathogen](https://github.com/tpope/vim-pathogen) and vim packages (vim ≥8, see
`:h packages`) compatible bundle.

Install
-------

You will need to have [Pathogen](https://github.com/tpope/vim-pathogen)
installed and working with your current vim setup. See
[these](https://github.com/tpope/vim-pathogen#installation) install instructions
of how to do this.

Once this is done, installing the SaC syntax file is as simple as:

```sh
$ cd ~/.vim/bundle
$ git clone https://github.com/SacBase/Vim.git vim-sac
```

Alternatively, you can use vim's packages
```sh
$ cd ~/.vim/pack/plugins/start
$ git clone https://github.com/SacBase/Vim.git vim-sac
```

Remember to reload `vim` afterwards :)
