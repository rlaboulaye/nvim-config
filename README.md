# nvim-config

## Requirements

- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation)
  - If lacking sudo, can install with conda
- Clipboard tool (xclip/xsel/win32yank or other depending on platform)
  - If lacking sudo, can install with conda
- A [Nerd Font](https://www.nerdfonts.com/): optional, provides various icons
  - if you have it set `vim.g.have_nerd_font` in `init.lua` to true
- Language Setup:
  - `npm`
  - `python`
    - `conda` recommended
  - `rust`
    - `rustup` recommended

## Installation

### Install Neovim

- Install [bob](https://github.com/MordechaiHadad/bob)
  - `cargo install bob-nvim`
- Install `nvim`
  - `bob install stable`

### Install Config

- `git clone https://github.com/rlaboulaye/nvim-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim`
- Start nvim with `nvim`

## More Information

For more information, refer to [Kickstart](https://github.com/nvim-lua/kickstart.nvim) on which this personal config is based
