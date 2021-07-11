# vimwiki-ghpages-template

This template makes it easy to get started with vimwiki and publishing your wiki to GitHub pages!

## Prerequisites

- [ ] vim-plug is installed
- [ ] vimwiki is installed
- [ ] docker is installed
- [ ] earthly is installed

## Setup

If you want to edit the wiki locally, you should clone the repo and add the following to the end of your `.vimrc` or `init.vim`:

```vim
source ~/path/to/this/repo/init.vim
```

This will add the repo's wiki to your `g:vimwiki_list`.

## Building

```sh
earthly +build
```

