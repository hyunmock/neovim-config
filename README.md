# Neovim Config

Personal Neovim configuration based on [LazyVim](https://github.com/LazyVim/LazyVim).

## Requirements

- Neovim >= 0.9.0
- Git
- A [Nerd Font](https://www.nerdfonts.com/) (optional, for icons)

## Installation

```bash
git clone git@github.com:hyunmock/neovim-config.git ~/.config/nvim
nvim
```

First launch will automatically install `lazy.nvim` and all plugins.

## Structure

```
~/.config/nvim/
├── init.lua              # Entry point
├── lazyvim.json          # LazyVim extras config
├── lua/
│   ├── config/
│   │   ├── lazy.lua      # Plugin manager setup
│   │   ├── options.lua   # Vim options
│   │   ├── keymaps.lua   # Custom keymaps
│   │   └── autocmds.lua  # Auto commands
│   └── plugins/
│       └── example.lua   # Plugin customization examples
└── stylua.toml           # Lua formatter config
```

## Customization

- **Options**: `lua/config/options.lua`
- **Keymaps**: `lua/config/keymaps.lua`
- **Plugins**: add `.lua` files under `lua/plugins/`

## References

- [LazyVim Docs](https://lazyvim.github.io)
- [lazy.nvim](https://github.com/folke/lazy.nvim)
