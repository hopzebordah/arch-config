# arch-config
a short script to insta-rice a new installation of arch

this is a script i have written to automatically configure
my arch installation to my preferences. i typically install 
from an arch-anywhere usb stick and then do all this manually,
this script just makes my life easier.

my arch-anywhere install consists of network-manager and i3 and nothing else.

TO USE:
	unpack the tarball with:
	
		tar -xvzf alexArchPostInstall.tar.gz
	
	enter the unpacked directory:
	
		cd alexArchPostInstall
	
	then just:
	
		sudo ./install.sh 
	
	it's also a good idea to reboot afterwards.

p.s. this program will not harm any of your files, EXCEPT for:
	.vimrc .zshrc .oh-my-zsh .xinitrc .Xdefaults .config/i3/config .config/termite/config
	 unless you uncomment line 3 of install.sh ;)
