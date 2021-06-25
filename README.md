# ARCH_CUSTOM_PKG ATTENTION ALPHA STATE

Program list :

tizonia-all (sudo pacman -Syu tizonia-all log4c)

traverso

yay

snapd

             and some dependicies compiled from AUR and private PKGBUILDs

/etc/pacman.conf
>>>>>>>>>>>>>>>>>>>>>>

[custom]

SigLevel = Optional TrustAll

Server = https://raw.github.com/devegoo/ARCH_CUSTOM_PKG/main/$arch

>>>>>>>>>>>>>>>>>>>>>>


and run:

sudo pacman -Syu tizonia-all traverso BlueMoon yay snapd
