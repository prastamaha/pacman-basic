# pacman basic command

mencari paket
	
	pacman -Ss neofetch

install paket

	sudo pacman -S neofetch

melihat informasi paket yang terinstall

	sudo pacman -Qi neofetch

menghapus paket

	sudo pacman -R neofetch

menghapus paket sekaligus depedensinya

	sudo pacman -Rs neofetch

update database/repo pacman
	
	sudo pacman -Sy

update semua aplikasi

	sudo pacman -Su

update database/repo sekaligus aplikasi

	sudo pacman -Syu

update satu aplikasi

	sudo pacman -S firefox

update beberapa aplikasi

	sudo pacman -s firefox vlc

melihat paket yang membutuhkan update

	sudo pacman -Qu

melihat paket tertentu yang membutuhkan update

	sudo pacman -Qu | grep python
