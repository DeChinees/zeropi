# zeropi RaspbeeII setup with Deconz.

Follow steps as described here: https://phoscon.de/en/raspbee2/install#raspbian
Additional steps:
If you encounter: Invalid argument ioctl() to /dev/rtc0 to read the time failed.
Fix rtc: sudo hwclock --systohc -D --noadjfile --utc
