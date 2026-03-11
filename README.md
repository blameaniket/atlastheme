**Inspiration**

I really like [atlas.vim](https://github.com/huyvohcmc/atlas.vim) colorscheme,
so i made it for neovim. Hope you like it.

## Installation

Install it with [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
return {
	"aniketmondal092009/atlastheme",
	name = "atlas.nvim",
	lazy = false,
	priority = 1000,

	config = function()
		require("atlas").setup({
			-- custom options
		})

		vim.cmd.colorscheme("atlas")
	end
}
```
