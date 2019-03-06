
Debian
====================
This directory contains files used to package hondaiscoinmnd/hondaiscoinmn-qt
for Debian-based Linux systems. If you compile hondaiscoinmnd/hondaiscoinmn-qt yourself, there are some useful files here.

## hondaiscoinmn: URI support ##


hondaiscoinmn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hondaiscoinmn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hondaiscoinmnqt binary to `/usr/bin`
and the `../../share/pixmaps/hondaiscoinmn128.png` to `/usr/share/pixmaps`

hondaiscoinmn-qt.protocol (KDE)

