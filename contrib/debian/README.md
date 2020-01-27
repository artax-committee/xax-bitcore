
Debian
====================
This directory contains files used to package xaxd/xax-qt
for Debian-based Linux systems. If you compile xaxd/xax-qt yourself, there are some useful files here.

## xax: URI support ##


xax-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xax-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xax-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

xax-qt.protocol (KDE)

