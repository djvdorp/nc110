# nc110

- Model: Samsung NC110-A03NL
- CPU: Intel Atom N550
- RAM: 1GB
- Disk: 128GB Samsung 830 SSD (custom)
- Platform: i686 (32 bit Intel x86 platform)
- Partition scheme: BIOS/MBR
- Bootloader: GRUB
- Cryptsetup: LVM on LUKS
- Device `/dev/sda1`: `/boot` (ext4, 200M)
- Device `/dev/sda2`: `cryptroot` (crypto_LUKS, 100%FREE)
