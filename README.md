# Bootstrap Snippets

HTML and Haml snippets for [Twitter Bootstrap 3.3.2](http://getbootstrap.com/) markup, for the Vim Plugins [snipMate](https://github.com/garbas/vim-snipmate) and [ultisnips](https://github.com/sirver/ultisnips).

![Animation](https://cloud.githubusercontent.com/assets/227274/5981940/c07ea88c-a901-11e4-859d-d87eeff19354.gif)

## Dependencies

- [ultisnips](https://github.com/sirver/ultisnips)

Or

- [vim-snipmate](https://github.com/garbas/vim-snipmate)
- [tlib\_vim](https://github.com/tomtom/tlib_vim)
- [vim-addon-mw-utils](https://github.com/MarcWeber/vim-addon-mw-utils)

## Installation using [Pathogen](https://github.com/tpope/vim-pathogen)

    $ cd ~/.vim
    $ mkdir bundle
    $ cd bundle

    # Install vim-snipmate dependencies:
    $ git clone https://github.com/garbas/vim-snipmate.git
    $ git clone https://github.com/tomtom/tlib_vim.git
    $ git clone https://github.com/MarcWeber/vim-addon-mw-utils.git

    # Install bootstrap-snippets
    $ git clone -b bootstrap-3-3-2 git://github.com/bonsaiben/bootstrap-snippets.git


## Usage

In an html or haml file, type a trigger name in Insert mode, and press `Tab` to expand it into HTML markup.

Trigger names are meant to be as predictable as possible without being too long or redundant.

Most trigger names correspond directly to the relevant tag or class name, minus hyphens. For example, `btnprimary` becomes:

```html
<button type="button" class="btn btn-primary">Default</button>
```

##### Buttons

Markup with `.btn` class uses the `<button>` tag by default, however there is usually a corresponding `<a>` tag version with the same trigger preceded by an `a`. For example, with `btnprimary` there is also `abtnprimary` which becomes:

```html
<a href="#" class="btn btn-primary" role="button">Primary</a>
```

See Trigger Glossary below for a full list of triggers.

## Filetypes

By default html snippets will only work in html files, or file formats associated with the html filetype in vim. If you are using a format like Ruby ERB (`.html.erb`) and the html snippets are not working, you may have to tell Vim to associate `.html.erb` files with the html filetype, for example:

```vim
autocmd BufRead,BufNewFile *.html.erb set filetype=html
```

## Autocomplete

bootstrap-snippets ships with a dictionary file containing all of the triggers. This can be used as a vim dictionary for autocomplete (Insert mode CTRL+N/CTRL+P).

Add the dictionary file and enable dictionary autocomplete:

```vim
set dictionary+=~/.vim/bundle/bootstrap-snippets/dictionary
set complete+=k
```

## Trigger Glossary

You can find a trigger glossary in the Wiki [here](https://github.com/bonsaiben/bootstrap-snippets/wiki/Trigger-Glossary).

