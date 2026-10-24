# Surya Flashing Guide (OrangeFox)
Read carefully this guide if you want to flash any custom ROM made by @kylieeXD

## Requirements
----------------
1. https://github.com/xiaomi-surya-devs/releases/releases/tag/OrangeFox-R11.1_6-Stable
2. lineage-24.0-xxxxxxxx-UNOFFICIAL-surya.zip

## Some Instructions
--------------------
1. Boot into bootloader use:
```
adb reboot bootloader
```

2. Flash vendor_boot use:
```
fastboot flash recovery /path/to/recovery.img
```

3. Reboot manually the device into recovery use:
```
fastboot reboot recovery
```

4. Wipe Data
```
Check Cache, Dalvik, Data, Metadata, then Swipe
```

5. Flash the ROM
```
Choose /path/to/lineage-24.0-xxxxxxxx-UNOFFICIAL-surya.zip, then Swipe
```

6. Format Data
```
Choose Format data, then type yes
```
