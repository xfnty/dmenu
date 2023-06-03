
# dmenu - dynamic menu
[dmenu](dwm.suckless.org) is an efficient dynamic menu for X.
It is also has a [page](https://wiki.archlinux.org/title/Dmenu) on Arch Wiki.


## Patches
- [center](https://tools.suckless.org/dmenu/patches/center/)
- [border](https://tools.suckless.org/dmenu/patches/border/)


## Installation
Edit `config.def.h` to match your local setup (dmenu is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install dmenu:
```
sudo make clean install
```
