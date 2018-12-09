
Debian
====================
This directory contains files used to package rimecoind/rimecoin-qt
for Debian-based Linux systems. If you compile rimecoind/rimecoin-qt yourself, there are some useful files here.

## rimecoin: URI support ##


rimecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rimecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rimecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/rimecoin128.png` to `/usr/share/pixmaps`

rimecoin-qt.protocol (KDE)

