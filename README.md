# Atlas

Dotfiles for my current Arch Linux setup featuring the
[atlas](https://github.com/huyvohcmc/atlas.vim) colour scheme. 

## Background

This is a setup tailored for my R use. I was using RStudio for my R work but then I found a more
minimal workflow could be achieved using Neovim and [Nvim-R](https://github.com/jalvesaq/Nvim-R) and
tmux. I also use [radian](https:github.com/randy3k/radian) for my R console as it also can be
integrated into Nvim-R. A few notes about this:

- This is still work in progress so you might have to keep pulling and reinstalling
- I use a very barebones tmux config. I'd highly recommend tweaking it to your use-case/preference
- I'm working on even setting up completions for R in Neovim (I currently use the default Nvim-R
  completions - see the Nvim-R 
  [documentation](https://raw.githubusercontent.com/jalvesaq/Nvim-R/master/doc/Nvim-R.txt) for more
  on this). I'v been trying to set up [ncm-R](https://github.com/gaalcaras/ncm-R) and am open to any
  inputs on setting this up.

## Installation

I generally recommend [`GNU stow`](https://www.gnu.org/software/stow/) for setting this up on your
machine but it ususally requires some packages to be installed first. I would suggest that anyone
interested in using this lookth through this first before running `stow`.


