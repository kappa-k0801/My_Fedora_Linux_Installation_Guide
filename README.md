# My_Fedora_Linux_Installation_Guide

## Use Net Install ISO
- Minimal installation using custom installation options
1) Download ISO
[Download Fedora Everything 44](https://fedoraproject.org/misc/#everything)
2) USe **"Fedora Custom Operation System"**
3) Install :)

## Install Gnome (Minimal)
1) Install Gnome
```
dnf install gnome-shell gdm nautilus fuse gvfs-fuse gvfs-mtp tar flatpak ptyxis
```
2) Booot Graphical Environment
```
sudo systemctl set-default graphical.target
sudo systemctl enable gdm
```
3) Enable Faltpak
```
sudo flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```

## Install the program according to personal needs
- Welcom to Gnome/Fedora Linux World :)
