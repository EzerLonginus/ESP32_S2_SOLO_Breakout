# ESP32_S2_SOLO_Breakout
Breakout Board for ESP32 S2 Solo

This board is a simple breakout for the ESP32 S2 Solo.  The interface includes the standard reset and boot button, with a USB to UART CP2012 converter, and a 3V3 regulator.  Also included is an LED on the GPIO 0 pin.  All GPIO pins are broken out to standard 2.54mm headers.  USB-C reseptacle connector is used, but at the USB 2.0 standard. 

## Purpose
This is mostly an excersize in designing an ESP32 module for inclusion in other projects.  Once this design is functional, I'll start using it as a template for more custom oriented projects involving the chip (or some variant).  I decided on the ESP S2 Solo, mostly because it was fairly inexpensive and I didn't see too many other breakouts utilizing it.  Depending on how this excersize goes, I may start designing boards with just the bare chip (no built in WiFi antenna, SPI Flash, etc).    

## Scematic
![ESP32 S2 Solo Schematic](hardware/ESP32_S2_Breakout/images/esp32_s2_solo_schematic.jpg)

## Layout
![ESP32 S2 Solo Layout](hardware/ESP32_S2_Breakout/images/esp32_s2_solo_layout.jpg)

## Current State of Affairs
### Version 1
* Populate and test board
* Upload some blink/hello world sketch
* Fix the inevitable issue that I missed during production

![Static Badge](https://img.shields.io/badge/espressif-ESP32-brightgreen)