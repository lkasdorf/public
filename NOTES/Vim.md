#linux #vim

# Neovim

- [Install Nvim Tree](https://linovox.com/install-and-use-nvim-tree-in-neovim/)
- [Install Which Key](https://linovox.com/install-and-set-up-which-key-in-neovim-nvim/)
- [Install and use Packer](https://linovox.com/install-and-use-packer-in-neovim/)
 - [Vim Cheat Sheet](https://vim.rtorr.com/)
 - [Vim cheatsheet - devhints](https://devhints.io/vim)

## Learnings

> :x or ZZ only writes when something is modified but using :wq modifies no matter what.. yeah this 'll make a difference on timestamp ~~(imagine when working on git repo)~~

> Instead of quitting and reopening, simply use `:e filename`. Or, if you want to open the file in readonly mode, then use `:view filename`. After that you have 2 buffers open, but you will only see one of them. That's when you need to learn how to navigate between buffers. You can use the `:ls` command to get a list of buffers and then you can select a buffer with `:b number` or `:b partial-filename`. If you want to look at buffers side-by side, you can use `:split` or `:vsplit` and then you can use ctrl+w hjkl to navigate between the different splits on your screen. After that you probably want to use the `:b` command again to select a specific buffer for a split.

### Links

 - [Learn to speak vim — verbs, nouns, and modifiers!](https://yanpritzker.com/learn-to-speak-vim-verbs-nouns-and-modifiers-d7bfed1f6b2d)
 - [Learning Vim as a Language: Nouns](https://douglasrumbaugh.com/post/vim-as-language-noun/)

Read more at `:h window`

## Youtube Videos

 - [Learn How to Use the Vim Text Editor (Episode 1) - Basic Usage (and how to exit Vim)](https://www.youtube.com/watch?v=wACD8WEnImo)
 - [Learn How to Use the Vim Text Editor (Episode 2) - Modes, Navigation and More](https://www.youtube.com/watch?v=yIxRhAzkhPk)
 - [Learn How to Use the Vim Text Editor (Episode 3) - Getting Started with Buffers](https://www.youtube.com/watch?v=JBKoBuuoF28)
 - [Learn How to Use the Vim Text Editor (Episode 4) - Visual Mode](https://www.youtube.com/watch?v=rOKL1pW1UUc)
 - [Learn How to Use the Vim Text Editor (Episode 5) - Splitting your Vim Window](https://www.youtube.com/watch?v=fBsxD6itAgw)
 - [Learn How to Use the Vim Text Editor (Episode 6) - Tips, Tricks and How to Configure Vim](https://www.youtube.com/watch?v=mW_YiBIJPo4)

# Neovim Kickstart

[The Best Editor](https://www.youtube.com/watch?v=WgXO2cvmdQc)

[kickstart.nvim (Github)](https://github.com/nvim-lua/kickstart.nvim)
