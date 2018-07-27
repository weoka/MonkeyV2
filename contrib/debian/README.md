
Debian
====================
This directory contains files used to package monkeyd/monkey-qt
for Debian-based Linux systems. If you compile monkeyd/monkey-qt yourself, there are some useful files here.

## monkey: URI support ##


monkey-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install monkey-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your monkeyqt binary to `/usr/bin`
and the `../../share/pixmaps/monkey128.png` to `/usr/share/pixmaps`

monkey-qt.protocol (KDE)

