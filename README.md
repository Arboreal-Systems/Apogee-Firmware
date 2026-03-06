# Apogee Firmware
Public repository of Apogee Controller firmware releases.

Navigate to releases and download the .hex file under the most recent version.

## How to load a .hex on your Apogee
1. Rename the downloaded .hex file to "apogee.hex" (**case-sensitive!**).
2. Place the "apogee.hex" file onto a USB thumb drive.
3. Shut down your Apogee (always by pulling the yellow trigger wire to allow graceful shutdown), remove the BLE dongle (if you are updating a Master Apogee) and insert your thumb drive.
4. Power-on your Apogee. The indicator light should go green and then flash yellow, which indicates it is updating, then it should transition to purple followed by solid green.
5. Remove the USB thumb drive and insert your BLE dongle.

*NOTE*: if the procedure described doesn't work, you may have an outdated bootloader on your Apogee. If this is the case, you will need to connect to the Apogee via bluetooth, press the "Firmware Upgrade" button in Settings and then follow the instructions from Step 4.
