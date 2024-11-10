# udev
```bash
# copy keyboard mappings db
sudo cp 61-eve-* /usr/lib/udev/hwdb.d/

# copy backlight rules
sudo cp 99-pixelbook-backlights.rules /usr/lib/udev/rules.d/

# Run commands
sudo systemd-hwdb update
sudo udevadm control --reload-rules
sudo udevadm trigger

# REBOOT
```

