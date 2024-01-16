## Neovim Personal Config

Personal config includes:

```lua
use "wbthomason/packer.nvim" -- Have packer manage itself
use "nvim-lua/popup.nvim"    -- An implementation of the Popup API from vim in Neovim
use "nvim-lua/plenary.nvim"  -- Useful lua functions used ny lots of plugins
use "windwp/nvim-autopairs"  -- Autopairs, integrates with both cmp and treesitter

-- Colorschemes
use "lunarvim/colorschemes" -- A bunch of colorschemes you can try out
use "polirritmico/monokai-nightasty.nvim"
use "/ku1ik/vim-monokai"

-- cmp plugins
use "hrsh7th/nvim-cmp"         -- The completion plugin
use "hrsh7th/cmp-buffer"       -- buffer completions
use "hrsh7th/cmp-path"         -- path completions
use "hrsh7th/cmp-cmdline"      -- cmdline completions
use "saadparwaiz1/cmp_luasnip" -- snippet completions
use "hrsh7th/cmp-nvim-lsp"
use "hrsh7th/cmp-nvim-lua"

-- snippets
use "L3MON4D3/LuaSnip"             --snippet engine
use "rafamadriz/friendly-snippets" -- a bunch of snippets to use

-- LSP
use "neovim/nvim-lspconfig"             -- enable LSP
use "williamboman/mason.nvim"           -- simple to use language server installer
use "williamboman/mason-lspconfig.nvim" -- simple to use language server installer
use 'jose-elias-alvarez/null-ls.nvim'   -- LSP diagnostics and code actions

-- Treesitter
use {
    "nvim-treesitter/nvim-treesitter",
    run = ":TSUpdate",
}
use "p00f/nvim-ts-rainbow"
use "nvim-treesitter/playground"

-- Telescope
use "nvim-telescope/telescope.nvim"
use 'nvim-telescope/telescope-media-files.nvim'
```

## Reference(s)

[Neovim-from-scratch](https://github.com/LunarVim/Neovim-from-scratch)

## LICENSE

[MIT](./LICENSE)
