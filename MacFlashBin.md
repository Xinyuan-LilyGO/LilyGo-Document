
#  Install ESPTool on macOS

Open a Terminal, and launch following commands:

```
python3 quit

```

If system asks about install Developer Tools, do it.

```
python3 -m pip install --upgrade pip
python3 -m pip install esptool
```

In order to launch esptool.py, exec directly with this:

```
python3 -m esptool
```

Alternatively, you can add Python binaries directory to PATH:

```
~/Library/Python/3.9/bin
```

For ESP32 use the following command to write

```
esptool --chip esp32  --baud 921600 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m 0x0 firmware.bin

```


For ESP32-C3 use the following command to write

```
esptool --chip esp32c3  --baud 921600 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m 0x0 firmware.bin

```

For ESP32-S3 use the following command to write

```
esptool --chip esp32s3  --baud 921600 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m 0x0 firmware.bin

```





