# dew-fox

OrangeFox R12 (fox_16.0 / Android 16) build for **Xiaomi Redmi 15C / POCO C85 (dew)**.

## Build

Actions tab → *OrangeFox R12 dew* → **Run workflow**.

Artefact: `OrangeFox-R12-dew` (recovery.img + vendor_boot.img).

## Flash

```bash
fastboot flash vendor_boot vendor_boot.img
fastboot reboot recovery
```

Device tree: [linastorvaldz/recovery_xiaomi_dew](https://github.com/linastorvaldz/recovery_xiaomi_dew) (fox-14.1, needs porting to fox_16.0).
