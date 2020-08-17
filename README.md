The font used in the screenshot is [Haskplex Nerd](https://github.com/huytd/haskplex-font).

## Installation

There are two way to use this config:

**Option 1:** Check `init.vim` and copy just what you need.

**Option 2:** Clone the whole repo in to `~/.config/nvim/`, please make sure you don't have this folder before clone:

```
$ git clone https://github.com/huytd/vim-config ~/.config/nvim/
```

## Screenshots

NERDTree + coc.nvim floating document + vista.vim outline:

![](https://i.imgur.com/NItTlei.png)

Floating Terminal: `<Leader>at` or `:call FloatTerm()`

![](https://i.imgur.com/tbANa2W.png)

NodeJS REPL: `<Leader>an` or `:call FloatTerm('"node"')`

![](https://i.imgur.com/SQYbYJA.png)

Floating tig - TUI Git: `<Leader>ag` or `:call FloatTerm('"tig"')`

![](https://i.imgur.com/zAjTPsK.png)

## Coc Install

```bash
:CocInstall coc-css coc-json coc-phpls coc-rls coc-tsserver coc-yaml
```

## Guide

### Move

- w: moves you to the beginning of the next word
- e: moves you to the last letter of the word
- i: lets you start editing right where the cursor is
- a: lets you start editing one character ahead

### Search

- Search text: \
