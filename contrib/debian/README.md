
Debian
====================
This directory contains files used to package faqod/faqo-qt
for Debian-based Linux systems. If you compile faqod/faqo-qt yourself, there are some useful files here.

## faqo: URI support ##


faqo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install faqo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your faqoqt binary to `/usr/bin`
and the `../../share/pixmaps/faqo128.png` to `/usr/share/pixmaps`

faqo-qt.protocol (KDE)

