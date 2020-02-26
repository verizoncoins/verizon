# Debian

This directory contains files used to package vrzd/vrz-qt
for Debian-based Linux systems. If you compile vrzd/vrz-qt yourself, there are some useful files here.

## vrz: URI support

vrz-qt.desktop (Gnome / Open Desktop)
To install:

    sudo desktop-file-install vrz-qt.desktop
    sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vrz-qt binary to `/usr/bin`
and the `../../share/pixmaps/vrz128.png` to `/usr/share/pixmaps`

vrz-qt.protocol (KDE)
