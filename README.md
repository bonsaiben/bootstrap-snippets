Bootstrap Snippets
==================

Work in progress

HTML and Haml snippet files for [Twitter Bootstrap 3.3.2](http://getbootstrap.com/), for the [snipmate](https://github.com/garbas/vim-snipmate) plugin for Vim.

Dependencies
------------

- [vim-snipmate](https://github.com/garbas/vim-snipmate)

How to install
--------------

- Install [vim-snipmate](https://github.com/garbas/vim-snipmate) and dependencies
- Install bootstrap-snippets

Installation using [Pathogen](https://github.com/tpope/vim-pathogen)
---------------------------

    $ cd ~/.vim
    $ mkdir bundle
    $ cd bundle
    $ git clone git://github.com/bonsaiben/bootstrap-snippets.git

    # Install dependencies:
    $ git clone https://github.com/garbas/vim-snipmate.git
    $ git clone https://github.com/tomtom/tlib_vim.git
    $ git clone https://github.com/MarcWeber/vim-addon-mw-utils.git

Usage
-----

Generally the snippet trigger will be the name of the relevant class or combination of classes (no hyphens).

For example, `btnprimary` becomes:

    %button.btn.btn-primary{:type => "button"} ${1:Default}

Notable exceptions to this rule:

- `abtn`
- `abtnblock`
- `abtndanger`
- `abtninfo`
- `abtninverse`
- `abtnlarge`
- `abtnmini`
- `abtnprimary`
- `abtnsmall`
- `abtnsuccess`
- `abtnwarning`
- `aclose`
- `adisabled`
- `btndropdown`
- `btndropdownsplit`
- `btndropup`
- `inputappendbtn`
- `inputappendbtndropdown`
- `inputprependappend`
- `navbarcollapse`
- `navpillsdropdown`
- `navpillsstacked`
- `navtabsdropdown`
- `navtabsstacked`
- `pageraligned`
- `progressstacked`
- `thumbnailsdiv`
