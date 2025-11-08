# Totem firmware with ZMK Studio Support

Original instructions:

  - fork this repo
  - git clone your repo, to create a local copy on your PC (you can use the command line or github desktop)
  - adjust the totem.keymap file (find all the keycodes on the zmk docs pages)
  - git push your repo to your fork
  - on the GitHub page of your fork navigate to "Actions"
  - scroll down and unzip the firmware.zip archive that contains the latest firmware
  - connect the left half of the TOTEM to your PC, press reset twice
  - the keyboard should now appear as a mass storage device
  - drag'n'drop the totem_left-seeeduino_xiao_ble-zmk.uf2 file from the archive onto the storage device
  - repeat this process with the right half and the totem_right-seeeduino_xiao_ble-zmk.uf2 file.
