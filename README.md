# blackview-tab15pro

Blackview Tab 15 Pro workdir

## Status

### Boot

1. Stock U-Boot
2. uniLoader
3. Linux

## postmarketOS

### Wiki

https://wiki.postmarketos.org/wiki/Blackview_Tab_15_Pro

## misc

### pack kernel

```sh
mkbootimg --header_version 4 --kernel vmlinuz --ramdisk initramfs --cmdline '' -o repacked_boot.img
```

### change slot

```
fastboot --set-active=b
```

### warnings

- don't pack empty initramfs
- don't erase vendor_boot

## Links

### U-Boot

https://github.com/akku1139/ums9230-mainline-u-boot

### Linux

https://github.com/akku1139/linux/tree/ums9230/blackview-tab15pro

### uniLoader

https://github.com/akku1139/uniLoader/tree/blackview-tab15pro

## See also

- https://github.com/faveoled/c35-mainline
- https://github.com/akku1139/android_device_blackview_tab15pro
