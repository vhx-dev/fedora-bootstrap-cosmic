dnf install   --installroot=/mnt   --releasever=40   --setopt=install_weak_deps=False   --setopt=keepcache=True   --nodocs   basesystem dnf dnf-plugins-core deltarpm systemd systemd-udev audit chrony glibc-langpack-en rootfiles btrfs-progs zstd ncurses binutils util-linux which less cracklib-dicts bash-completion sudo nano NetworkManager-wifi NetworkManager-tui grub2-efi-x64 grub2-efi-x64-modules efibootmgr efivar kernel-longterm lz4 realtek-firmware atheros-firmware bluez-firmware bluez mesa-dri-drivers neofetch htop mlocate pipewire wireplumber zram-generator-defaults cosmic-desktop cosmic-term cosmic-files 

after reboot
restoreconf -R /home
dracut -Nfv --regenerate-all
