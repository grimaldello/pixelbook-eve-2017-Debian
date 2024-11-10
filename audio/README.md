# Copy all folders/files in corresponding system dirs
```bash
# Run the following commands from the repository audio folder
sudo cp -r opt/google/dsm/dsmparam.bin /opt/google/dsm/dsmparam.bin
sudo cp -r lib/firmware/9d71-GOOGLE-EVEMAX-0-tplg.bin /lib/firmware/9d71-GOOGLE-EVEMAX-0-tplg.bin
sudo cp -r lib/firmware/dsp_lib_dsm_core_spt_release.bin /lib/firmware/dsp_lib_dsm_core_spt_release.bin
sudo cp -r lib/firmware/intel/dsp_fw_C75061F3-F2B2-4DCC-8F9F-82ABB4131E66.bin /lib/firmware/intel/dsp_fw_C75061F3-F2B2-4DCC-8F9F-82ABB4131E66.bin

# ucm2 configuration
sudo cp -r usr/share/alsa/ucm2/conf.d/kbl-r5514-5663- /usr/share/alsa/ucm2/conf.d/kbl-r5514-5663-
sudo cp -r usr/share/alsa/ucm2/Intel/kbl-r5514-5663- /usr/share/alsa/ucm2/Intel/kbl-r5514-5663-

# Install firmware dependencies
sudo apt install firmware-intel-sound

# REBOOT
```


# Minor issues
- No automatic switch to headphone when inserted and vice versa (need to manually switch it from System Audio Icon, not a big deal)