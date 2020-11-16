
Debian
====================
This directory contains files used to package bitcoinnewd/bitcoinnew-qt
for Debian-based Linux systems. If you compile bitcoinnewd/bitcoinnew-qt yourself, there are some useful files here.

## bitcoinnew: URI support ##


bitcoinnew-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinnew-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinnewqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinnew128.png` to `/usr/share/pixmaps`

bitcoinnew-qt.protocol (KDE)

