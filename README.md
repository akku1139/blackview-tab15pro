# blackview-tab15pro

Blackview Tab 15 Pro workdir

## postmarketOS

### Wiki

https://wiki.postmarketos.org/wiki/Blackview_Tab_15_Pro

## misc

### pack kernel

```sh
mkbootimg --header_version 4 --kernel vmlinuz --ramdisk initramfs --cmdline '' -o repacked_boot.img
```
