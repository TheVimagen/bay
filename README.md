## Introduction
This is an Arch Linux post installation script, it installs what I call "BAY", my desktop environment that uses my custom builds of [suckless](https://suckless.org/) software. The script also installs my dotfiles, my default programs, the "yay" AUR helper and modifies pacman.conf and makepkg.conf.

## Installation
This script is intended to be ran in a fresh install of Arch linux with no display manager(gui login screen). I use this script after using archinstall with the "xorg" profile selected.

**Run this script as a regular user.**
```
git clone --depth 1 https://gitlab.com/SamDenton/samde.git
cd bay
./bay.sh

```

## Credit
This was mainly inspired by [LARBS](https://larbs.xyz/) and [chadwm](https://github.com/siduck/chadwm).

I would like to give big thank you to suckless and all the people who've made patches for the suckless programs.

Thank you to the creators of [dmenu-bluetooth](https://github.com/Layerex/dmenu-bluetooth) and [lfub](https://github.com/LukeSmithxyz/voidrice/blob/master/.local/bin/lfub).

Also last but not least I would like to thank the FOSS community. This project would have not been possible to make with proprietary software.
