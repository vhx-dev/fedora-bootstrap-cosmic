dnf install   --installroot=/mnt   --releasever=40   --setopt=install_weak_deps=False   --setopt=keepcache=True   --nodocs   basesystem dnf dnf-plugins-core deltarpm systemd systemd-udev glibc-langpack-en rootfiles btrfs-progs zstd ncurses binutils util-linux which less cracklib-dicts bash-completion sudo nano NetworkManager-wifi NetworkManager-tui grub2-efi-x64 grub2-efi-x64-modules efibootmgr efivar kernel-longterm realtek-firmware atheros-firmware neofetch htop pipewire wireplumber cosmic-desktop zram-generator-defaults

after reboot
restoreconf -R /home
