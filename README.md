<h2><p align="center">voidinstall</p></h2>   

### How to use

1. Log in as root (password is `voidlinux`)
2. Load your keymap and other conviniences like bash
3. Update xbps and install git
4. Clone this repository
5. cd into `voidinstall`
7. Run `install.sh` (still as root)

### Copy and paste

```
xbps-install -S git
git clone https://github.com/me00000000000/voidinstall
cd voidinstall
./installer.sh
```

### About

This is a custom version, simplified and maybe personal, forked from [kkrruumm/void-install-script](https://github.com/kkrruumm/void-install-script)

Main changes:
- Defaults to btrfs (and removes xfs)
- Defaults to no swap
- Defaults to no LVM
- Defaults to UKI
- Defaults to default repos
- Defaults to 'none' in desktop choice

Desktop changes:
- Removed sway, swayfx, niri and wayfire as desktop options
- Installs firefox in all desktops (except in 'none')
- In i3, adds i3status, dmenu, xclip, setxkbmap, etc.
- In xfce4, adds xfce4-plugins
