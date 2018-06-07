
Debian
====================
This directory contains files used to package hashrentalcoind/hashrentalcoin-qt
for Debian-based Linux systems. If you compile hashrentalcoind/hashrentalcoin-qt yourself, there are some useful files here.

## hashrentalcoin: URI support ##


hashrentalcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hashrentalcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hashrentalcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/hashrentalcoin128.png` to `/usr/share/pixmaps`

hashrentalcoin-qt.protocol (KDE)

