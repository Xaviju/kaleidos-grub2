# Kaleidos GRUB2 theme

A Kaleidos GRUB2 theme.

<img src="./preview.png" width="600">

## How to install

Save this theme at `/usr/share/grub/themes/kaleidos-theme`

Edit the following line in `/etc/default/grub`

```bash
GRUB_THEME="/usr/share/grub/themes/kaleidos-theme/theme.txt"
```

Re-generate `grub.cfg` to apply the changes.

```bash
# grub-mkconfig -o /boot/grub/grub.cfg
```

Reboot to see the changes

## Author

Xaviju for [Kaleidos](https://kaleidos.net)
