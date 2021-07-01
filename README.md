# Arch Install Notes

## Steps

- archinstall
- ``
### Wifi
- `iwctl`, type station, press `Tab` and see self-explaining auto completions

### GRUB
- Boot from live archlinux media
- mount /dev/sdxx /mnt (sdxx is your root partition)
- arch-chroot /mnt
- grub-mkconfig -o /boot/grub/grub.cfg
- grub-install

## Resources
- [Wiki](https://wiki.archlinux.org/title/installation_guide)
