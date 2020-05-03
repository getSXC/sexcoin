
Debian
====================
This directory contains files used to package sexcoind/sexcoin-qt
for Debian-based Linux systems. If you compile sexcoind/sexcoin-qt yourself, there are some useful files here.

## bitcoin: URI support ##


sexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sexcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/sexcoin128.png` to `/usr/share/pixmaps`

sexcoin-qt.protocol (KDE)

