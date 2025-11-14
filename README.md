# Totem firmware with Mouse and ZMK Studio Support

## Maintenance

  - adjust the totem.keymap file (find all the keycodes on the zmk docs pages)
  - commit your changes
  - Go to "Actions" on Github, scroll down and unzip the firmware.zip artifact
  - connect the left half of the TOTEM to your PC, press reset twice
  - the keyboard should now appear as a mass storage device
  - drag'n'drop the totem_left-seeeduino_xiao_ble-zmk.uf2 file from the archive onto the storage device
  - repeat this process with the right half and the totem_right-seeeduino_xiao_ble-zmk.uf2 file.
  - in case there are any issues, flash the reset image first and then the normal firmware
