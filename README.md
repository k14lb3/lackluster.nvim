# lackluster
> a delightful grayscale colorscheme thats soft on the eyes

![a screenshot of neovim with the lackluster colorscheme](./asset/lackluster.png)

![a picture of lackluster lualine variations](./asset/lackluster-lualine.png)

## INSTALL
1. Install `slugbyte/lackluster.nvim` with your favorite package manager
2. Set your colorscheme to `lackluster`

```lua 
-- example lazy.nvim install setup
return {
    "slugbyte/lackluster.nvim",
    lazy = false,
    priority = 1000,
    init = function()
        vim.cmd.colorscheme("lackluster")
    end,
}
```

## LUALINE
```lua
require('lualine').setup({
    options = {
        theme = "lackluster",
    },
})
```

## HELP WANTED
Suggestions and bug fixes, or help with expanding plugin support are appreciated :)

See the [Contributing Guide](./CONTRIBUTING.md)

## SELF-PROMO
If you like this project star the GitHub repository :)


## Supported plugins
* [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
* [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)
* [nvim-lightbulb](https://github.com/kosayoda/nvim-lightbulb)
* [nvim\_cmp](https://github.com/hrsh7th/nvim-cmp)
* [oil.nvim](https://github.com/stevearc/oil.nvim)
* [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
* [which-key.nvim](https://github.com/folke/which-key.nvim)
