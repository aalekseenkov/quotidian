
# Quotidian

An extension of the port of Sublime's Mariana/Juliana Theme for Neovim.

## Palette

| name        |                           hex                            | name         |                           hex                            |
| :---------- | :------------------------------------------------------: | :----------- | :------------------------------------------------------: |
| fg1         | ![#ffffff](https://placehold.co/15x15/ffffff/ffffff.png) | fg2          | ![#d8dee9](https://placehold.co/15x15/d8dee9/d8dee9.png) |
| fg3         | ![#a6acb9](https://placehold.co/15x15/a6acb9/a6acb9.png) | fg4          | ![#46525c](https://placehold.co/15x15/46525c/46525c.png) |
| bg1         | ![#444e59](https://placehold.co/15x15/444e59/444e59.png) | selection_bg | ![#3f4750](https://placehold.co/15x15/3f4750/3f4750.png) |
| bg2         | ![#303841](https://placehold.co/15x15/303841/303841.png) | bg3          | ![#2e353e](https://placehold.co/15x15/2e353e/2e353e.png) |
| diff_text   | ![#373f48](https://placehold.co/15x15/373f48/373f48.png) | diff_change  | ![#585249](https://placehold.co/15x15/585249/585249.png) |
| diff_remove | ![#4f434a](https://placehold.co/15x15/4f434a/4f434a.png) | text_fg      | ![#d9d9d9](https://placehold.co/15x15/d9d9d9/d9d9d9.png) |
| yellow1     | ![#fac761](https://placehold.co/15x15/fac761/fac761.png) | yellow2      | ![#f9ae58](https://placehold.co/15x15/f9ae58/f9ae58.png) |
| yellow3     | ![#ee932b](https://placehold.co/15x15/ee932b/ee932b.png) | green        | ![#99c794](https://placehold.co/15x15/99c794/99c794.png) |
| magenta     | ![#c695c6](https://placehold.co/15x15/c695c6/c695c6.png) | orange       | ![#f97b58](https://placehold.co/15x15/f97b58/f97b58.png) |
| red1        | ![#c76b70](https://placehold.co/15x15/c76b70/c76b70.png) | red2         | ![#ec5f66](https://placehold.co/15x15/ec5f66/ec5f66.png) |
| blue1       | ![#95b2d6](https://placehold.co/15x15/95b2d6/95b2d6.png) | blue2        | ![#5c99d6](https://placehold.co/15x15/5c99d6/5c99d6.png) |
| cyan1       | ![#87c7c7](https://placehold.co/15x15/87c7c7/87c7c7.png) | cyan2        | ![#5fb4b4](https://placehold.co/15x15/5fb4b4/5fb4b4.png) |

## Requirements

- `NVIM v0.10.0-dev`
- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - for better syntax highlighting

## Installation

- [Lazy](https://github.com/folke/lazy.nvim)

```lua
{
  'aalekseenkov/quotidian',
  lazy = false,
  opts = { --[=[ configuration --]=] },
  config = true,
}
```

## Configuration

```lua
{
  colors = {
    bg1          = '#444e59',
    bg2          = '#303841',
    bg3          = '#2e353e',
    blue1        = '#95b2d6',
    blue2        = '#5c99d6',
    cyan1        = '#87c7c7',
    cyan2        = '#5fb4b4',
    diff_add     = '#41525a',
    diff_change  = '#585249',
    diff_remove  = '#4f434a',
    diff_text    = '#373f48',
    fg1          = '#ffffff',
    fg2          = '#d8dee9',
    fg3          = '#a6acb9',
    fg4          = '#46525c',
    green        = '#99c794',
    magenta      = '#c695c6',
    orange       = '#f97b58',
    red1         = '#c76b70',
    red2         = '#ec5f66',
    selection_bg = '#3f4750',
    text_fg      = '#d9d9d9',
    yellow1      = '#fac761',
    yellow2      = '#f9ae58',
    yellow3      = '#ee932b',
  }
}
```

## Plugin Support

- [coc-nvim](https://github.com/neoclide/coc.nvim)
- [fennel.vim](https://github.com/bakpakin/fennel.vim)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [nvim-notify](https://github.com/rcarriga/nvim-notify)
- [nvim-semantic-tokens](https://github.com/theHamsta/nvim-semantic-tokens)
- [nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua)
- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [nvim-ts-rainbow](https://github.com/p00f/nvim-ts-rainbow)
- [nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons)
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [vim-sneak](https://github.com/justinmk/vim-sneak)
- and more...

## Credits

- [nvim-juliana](https://github.com/kaiuri/nvim-juliana) - port of Sublime's Mariana Theme for Neovim
- [Mariana](http://www.sublimetext.com/) - Sublime HQ Pty Ltd, Dmitri Voronianski
- [Todd Wolfson](https://github.com/twolfson/sublime-files) for the initial [palette](https://github.com/twolfson/sublime-files/blob/master/Packages/Color%20Scheme%20-%20Default/Mariana.sublime-color-scheme)
