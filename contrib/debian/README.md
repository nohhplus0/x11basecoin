
Debian
====================
This directory contains files used to package x11basecoind/x11basecoin-qt
for Debian-based Linux systems. If you compile x11basecoind/x11basecoin-qt yourself, there are some useful files here.

## x11basecoin: URI support ##


x11basecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install x11basecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your x11basecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/x11basecoin128.png` to `/usr/share/pixmaps`

x11basecoin-qt.protocol (KDE)

