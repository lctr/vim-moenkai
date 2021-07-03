vim-moenkai
===========

* Theme forked from [fratajczak/one-monokai-vim](https://github.com/fratajczak/one-monokai-vim)
* Colors adopted from [tgreen7/vscode-one-monokai](https://github.com/tgreen7/vscode-one-monokai)

Install
-------

### [vim-plug](https://github.com/junegunn/vim-plug)

    Plug 'lctr/vim-moenkai/'

### Manually

```bash
mkdir -p ~/.vim/colors
```
    
Download the `colors/moenkai.vim` file from the repo to `~/.vim/colors`

Usage
-----

Add the command below to your `~/.vimrc`:

```VimL
syntax on
colorscheme moenkai
```

Terminal support
----------------

If you are using a terminal which supports truecolor like **iterm2**, enable the gui color by adding the setting below in `~/.vimrc` or `~/.vim/init.vim`

```VimL
set termguicolors
```

Otherwise, use below setting to activate the 256 colors in your terminal

```VimL
set t_Co=256
```

Configuration
-------------

### Italic

By default the gui enables italic but not the terminal. They both can be configured.
    
If you are using a font that supports italic, paste the command below in your `.vimrc` to turn on terminal italic:

    let g:moenkai_term_italic = 1
    let g:moenkai_gui_italic = 1

Screenshots
-----------

![Screenshot](moenkai.png)
