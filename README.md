# ARCH_CUSTOM_PKG

/etc/pacman.conf

[custom]
SigLevel = Optional TrustAll
Server = https://raw.github.com/devegoo/ARCH_CUSTOM_PKG/main/$arch

pacman -Sy
