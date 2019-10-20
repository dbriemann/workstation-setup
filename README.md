# workstation-setup

Detailed listing of all tools and settings needed for my perfect development workstation. Currently running on Ubuntu Mate. These are just notes for myself.

## Tools

### Custom Install

- [fzf](https://github.com/junegunn/fzf)
- [gvm](https://github.com/moovweb/gvm)
- [vscode](https://code.visualstudio.com/download)
- [abricotine](https://abricotine.brrd.fr/#download)

### Apt Install

`rofi plank terminator tilix dconf-editor clang lua luajit xscreensaver* fd-find vim`

## Mate Settings

Important dconf settings for Mate are stored [here](mate-settings), these are mainly custom keybindings. After exporting the file is stripped of several settings. Don't just overwrite the old file!

**Export with:** `dconf dump /org/mate/ > org.mate`
**Import with:** `dconf load /org/mate/ < org.mate`

## Vscode Settings

All settings are stored in [settings.json](vscode-settings/settings.json).
