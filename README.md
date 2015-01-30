# Bootstrap Snippets

Work in progress

HTML and Haml snippet files for [Twitter Bootstrap 3.3.2](http://getbootstrap.com/), for the [snipmate](https://github.com/garbas/vim-snipmate) plugin for Vim.

## Dependencies

- [vim-snipmate](https://github.com/garbas/vim-snipmate)
- [tlib\_vim](https://github.com/tomtom/tlib_vim)
- [vim-addon-mw-utils](https://github.com/MarcWeber/vim-addon-mw-utils)

## Installation using [Pathogen](https://github.com/tpope/vim-pathogen)

    $ cd ~/.vim
    $ mkdir bundle
    $ cd bundle

    # Install dependencies:
    $ git clone https://github.com/garbas/vim-snipmate.git
    $ git clone https://github.com/tomtom/tlib_vim.git
    $ git clone https://github.com/MarcWeber/vim-addon-mw-utils.git

    # Install bootstrap-snippets
    $ git clone -b bootstrap-3-3-2 git://github.com/bonsaiben/bootstrap-snippets.git


## Usage

Snippet triggers are meant to be as predictable as possible without being too long.

Most triggers correspond directly to the name of the relevant tag or class name, minus hyphens. For example, `btnprimary` becomes:

    <button type="button" class="btn btn-primary">Default</button>

By default markup with `.btn` class uses `<button>` tag, however there is usually an `<a>` tag version with the same trigger preceded by an `a`. For example, with `btnprimary` there is also `abtnprimary` which becomes:

    <a href="#" class="btn btn-primary" role="button">Primary</a>

See Trigger Glossary below for a full list of triggers.

## Autocomplete

bootstrap-snippets ships with a dictionary file containing all of the triggers. This can be used as a vim dictionary for autocomplete (Insert mode CTRL+N/CTRL+P).

To enable autocomplete, add the dictionary file to dictionary settings and include dictionaries in complete setting:

```vim
set dictionary+=~/.vim/bundle/bootstrap-snippets/dictionary
set complete+=k
```

## Trigger Glossary

You can find a trigger glossary in the Wiki [here](https://github.com/bonsaiben/bootstrap-snippets/wiki/Trigger-Glossary).
