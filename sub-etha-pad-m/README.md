# Sub-Etha Pad M

![Sub-Etha Pad 0.95](https://github.com/piit79/Sub-Etha-Pad/raw/main/sub-etha-pad-m/Sub-Etha-Pad-M.jpg)

## Features

* Large aluminium CNC rotary encoder with 100 steps per rotation
* 8 keys
* Kailh hotswap sockets
* 6 RGB underglow LED modules (SK6812 MINI-E)
* 1 in-switch RGB LED and/or 1 up-facing RGB LED for indications
* 0.91" 128x32 OLED screen
* TRRS socket for daisy-chaining (pending firmware support)

## Revision history

### 1.1 (29/08/2022)
* Fixed OLED _again_ (rotated 180º so that the pins don't interfere with the Pro Micro USB-C socket)
* Fixed CNC encoder mounting holes (added pads to protect the PCB)
* Moved upwards-facing RGB LEDs to the end of the chain and made them independent

### 1.0 (11/07/2022)
* Fixed OLED (added I²C pullup resistors)
* Moved RGB underglow LEDs inwards for better light dispersion
* Added support for vertical 2u key at the bottom right
* Added in-switch RGB LED for the top right key / another up-facing RGB LED for indications (same colour when using both)
* Added TRRS socket for future daisy-chaining from other 42. Keebs keyboards (e.g. Mysterium) to avoid having to use multiple USB cables
* ⚠️ Known issues: OLED footprint pins interfere with the Pro Micro USB-C socket

### 0.95 (07/12/2021)
* Initial version
* ⚠️ Known issues: OLED not working due to missing I²C pullup resistors
