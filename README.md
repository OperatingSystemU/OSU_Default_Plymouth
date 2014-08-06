#Operating System U boot screen#

This is the default version of Operating System U boot screen.

##Installation##
	git clone https://github.com/awmrozek/OSU_Default_Plymouth.git
	cd OSU_Default_Plymouth
	sudo mkdir /usr/share/plymouth/themes/osu
	sudo cp -av * /usr/share/plymouth/themes/osu/

	sudo plymouth-set-default-theme osu
	sudo update-initramfs -u

##Switching##

Switching between the two installed themes can be easily accomplished by:

	sudo plymouth-set-default-theme osu
	sudo update-initramfs -u


Just change osu-simple to osu
