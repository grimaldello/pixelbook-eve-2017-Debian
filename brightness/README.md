# Backlight brightness fix
```bash
# Use DPCD for backlight
# Add configuration for kernel module i915
sudo echo 'options i915 enable_dpcd_backlight=1' >> /etc/modprobe.d/i915.conf

# Update initramfs
sudo update-initramfs -u -k all

# REBOOT
```

