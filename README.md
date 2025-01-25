[my-sensible.nvim](https://github.com/javier-lopez/my-sensible.nvim) is a global plugin who set preferences according to they way I use [neovim](https://neovim.io). It sets highly opinionated settings. Probably not something you would like to use straight ahead. Some of the included features are:

- A single config can be used across Windows, Mac and linux
- Eliminates swap and backup files from littering directories, preferring to store in a central location.
- Improve performance by disabling ancient tty options
- Enhance command completion, syntax highlighting and and search features
- Etc

Requirements
------------

* NeoVim 0.10

Installation
------------

- [Lazy.nvim](https://github.com/folke/lazy.nvim) way (recommended), add the following to your $HOME/.config/nvim/init.lua file:

        "javier-lopez/my-sensible.nvim"

    And run inside of vim:

        :Lazy
