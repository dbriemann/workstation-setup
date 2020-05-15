# workstation-setup

Detailed listing of all tools and settings needed for my perfect development workstation. Currently running on Ubuntu Mate. These are just notes for myself.

## Tools

### Custom Install

- fuzzy finder and dir jumps: [fzf](https://github.com/junegunn/fzf)
- go version manager: [gvm](https://github.com/moovweb/gvm)
- multi-language ide/editor: [vscode](https://code.visualstudio.com/download)
- cat alternative: [bat](https://github.com/sharkdp/bat) 
- ls alternative: [exa](https://the.exa.website/)
- git repo information in bash prompt: [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt)
- [neovim](https://github.com/neovim/neovim/wiki/Installing-Neovim#pre-built-archives-1)

### Apt Install

`rofi plank terminator tilix dconf-editor clang lua5.3 git luajit fd-find vim ripgrep nnn ncdu tig`

## Mate Settings

Important dconf settings for Mate are stored [here](mate-settings), these are mainly custom keybindings. After exporting the file is stripped of several settings. Don't just overwrite the old file!

**Export with:** `dconf dump /org/mate/ > org.mate`

**Import with:** `dconf load /org/mate/ < org.mate`

## Vscode Settings

All settings are stored in [settings.json](vscode-settings/settings.json).
