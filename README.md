<h1 align="center">atlas.nvim</h1>

<p align="center">
A minimalist colorscheme for <a href="https://github.com/neovim/neovim">Neovim</a> written in Lua.
</p>

<p align="center">
  <img src="assets/screenshot.png" width="800"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Neovim-0.8+-57A143?style=for-the-badge&logo=neovim" />
  <img src="https://img.shields.io/badge/Made%20with-Lua-blue?style=for-the-badge&logo=lua" />
  <img src="https://img.shields.io/github/stars/aniketmondal092009/atlastheme?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/aniketmondal092009/atlastheme?style=for-the-badge" />
</p>


## ✨ Features

- Minimal and clean color palette
- Monochrome
- Fully written in **Lua**
- Designed for modern **Neovim**
- Inspired by the original [atlas.vim](https://github.com/huyvohcmc/atlas.vim) colorscheme


## 📦 Installation

Install using **lazy.nvim**

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

## ⚙️ Configuration

Default configuration:

```lua
require("atlas").setup({
  variant = "main",

  disable_background = false,

  styles = {
    italic = false,
  },
})
```

## Inspiration

This colorscheme is inspired by the original [atlas.vim](https://github.com/huyvohcmc/atlas.vim) 
and ThePrimeagen's rose-pine theme.

It has been rewritten in **Lua** to better integrate with modern **Neovim** 
configurations and plugin ecosystems.


## Contributing

We welcome and appreciate contributions of any kind. Create an issue or start a
discussion for any proposed changes. Pull requests are encouraged for supporting
additional plugins or treesitter improvements.

Feel free to update the wiki with any recipes.


## License

This project is licensed under the **MIT License**.

See the [`LICENSE`](./LICENSE) file for more information.
