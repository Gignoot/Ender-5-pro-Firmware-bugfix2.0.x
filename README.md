# Ender-5-pro-Firmware-bugfix2.0.x
Flashable Firmware for ender 5 and ender 5 pro stock , without bed leveling probe or filament runout sensor.

This firmware is for Ender 5 and Ender 5 pro that come in stock version.

This firmware does not support a bed leveling probe or a filament runout sensor.

Firmware includes : 

-Universal Bed Leveling , to be done manual with a shim (feeler gauge) preferably 0.1 mm.

-Bed corner leveling.

-Filament change via menu (tuned for the long bowden tube).

-Autotemp and PID (autotune)

-Supports ARC and Junction deviation. (NO Linear Advance)

-EEPROM storage in onboard memory instead of SDCARD.

-5 different material preheat menus (PLA,ASA,PET,PP,TPU)

-Power outage rescue function

Note: print cooling fan needs a minimum of 20% setting in your slicer software before it will start spinning.


Instructions to Flash the firmware:

Put the firmware_20210320-220916.bin file on your SDCARD , turn off your printer, insert the sdcard into your printer and turn on the printer.

Wait a few seconds for the bleu screen to go away and the initial boot screen appears.

Go to advanced menu , and all the way at the bottom select "Initialize EEPROM", and confirm.

You are ready to go with the latest firware and options.

Succes.
