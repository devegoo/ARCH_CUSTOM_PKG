# ARCH_CUSTOM_PKG

Program list :

tizonia-all

traverso

BlueMoon

yay

snapd

             and some dependicies compiled from AUR and private PKGBUILDs

/etc/pacman.conf

[custom]

SigLevel = Optional TrustAll

Server = https://raw.github.com/devegoo/ARCH_CUSTOM_PKG/main/$arch

pacman -Sy
