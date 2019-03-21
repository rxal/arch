## ARCH INSTALL SCRIPT. USE AT YOUR OWN RISK.

**My setup: Lenovo X1 Carbon 120GB SSD (GPT-UEFI)**

**Boot into the arch install media and run the following commands.**

wifi-menu # For wifi

pacman -Sy reflector git

reflector --verbose -l 100 -p http -p https --sort rate --save /etc/pacman.d/mirrorlist

git clone https://github.com/rxal/arch

/bin/bash arch/install

**Login by entering your username and password.**

ls # To list available desktop environments

./name_of_desktop_environment

**Enjoy.**
