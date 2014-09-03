# Pathogen

To easily install plugins

https://github.com/tpope/vim-pathogen

# Tagbar

With the line `nmap <F8> :TagbarToggle<CR>` in my `.vimrc`, I can toggle the tagbar with the <F8> key (for Mac users, you have to make sure functions keys are treated as such by setting the appropriate setting in your system preferences).

## How to use it

- `<F8>`: open or close the tagbar
- `ctr-w` and `w`: switch to the tagbar. Instead of that last `w`, you can also use `h`, `l`, `k` or `j`.
- When you are in the tagbar, navigate to a word and press enter: the cursor in the file will jump to that definition.

http://majutsushi.github.io/tagbar/

# vim-javascript-syntax

I merely use this plugin because it causes vim to correctly fold JavaScript code, which I couldn't get right with the default folding settings.

## Basic folding operations:

- `zo`: open a fold
- `zc`: close a fold

https://github.com/jelera/vim-javascript-syntax

# YouCompleteMe

Code completion for python (amongst others). To install YCM, I needed to install [MacVim](https://code.google.com/p/macvim/].

http://valloric.github.io/YouCompleteMe/
