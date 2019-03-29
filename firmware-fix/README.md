## firmware-fix

For some weird reason, sometimes the player will refuse to update.
If you go to Settings -> Firmware Update, and get this error: "Updater v1.1 | v_v Failed", try with this modified firmware.

## Fix

To make these fixed images:
Unpack the image (as an iso, for example), and edit VERSION.TXT:
modify
```
ver=(...)
```
to this:
```
ver=2018-10-07T00:00:00+08:00
```

Then, repack the image, move to sdcard, and update as usual.

