<p align="center">
   <img src="./icon/binaryninja.png" alt="Binary Ninja logo" height="200">
</p>

# BinaryNinja Configuration and Installation

## TL;DR
Based off of my setup I've made this script that should download the latest version of binaryninja, add my custom configuration, and create a `.desktop` file

> [!WARNING]
> This is ONLY tested on my own setup. I try not to be dumb, so this script should work on most linux-based systems, but I won't test it. As long as it works on my machines using my setups I'm happy. Use at your own risk!

```bash
curl .../setup.sh | sh
```

## Installation

## Configuration

### .desktop file

### Keybinds
Since vim-bindings always are superior I've made some rebinds. Here are **some** of the most important keybindings from my `./keybindings.json`.
Also, if you know vim, you know the ***leader-key**, in this scenario my leader key is `Space`.
| Action | Keys |
| -------------- | --------------- |
| Cursor Movement | `h/j/k/l` |
| Command Palette | `:` |
| Graph | `gg` |
| High Level IL | `gc` (*go code*) |
| Go to Address | `ga` |
| Disassembly | `gd` |
| Strings | `gs` |
| Hex View | `gh` |
| Linear View | `gl` |
| Focus Find | `/` |
| Find Next | `n` |
| Move Cursor to End of Line | `$` |
| Move Cursor to Start of Line | `_` |
| Toggle Symbols View | `<leader>s` |
| Toggle Memory Map View | `<leader>m` |
| Toggle Mini Graph View | `<leader>g` |
| Copy | `yy` |
| Copy Address | `ya` |
| <++> | `<++>` |
| <++> | `<++>` |
| <++> | `<++>` |
| <++> | `<++>` |
| <++> | `<++>` |
| <++> | `<++>` |
