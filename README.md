# grbl-teensy-4
GRBL Breakout Boards for Teensy 4.x Uses the [grblHAL Teensy 4 version](https://github.com/terjeio/grblHAL).

## June 28, 2020. New Versions!

I am putting the finishing touches on 2 new 5 axis versions based on the Teensy 4.1. One supports an Ethernet interface and the other supports a USB interface. I will be making a few "Unkit" boards avalable. These have all the surface mount components installed (with the execption of the EEPROM IC). Teensy 4.1 not included. I haven't finalized pricing but probably in the mid-$20 range. Check back here for more details.

T41U5XBB - USB based version.  
![T4.1 BreakoutBoard](https://github.com/phil-barrett/grbl-teensy-4/blob/master/R6278732_DxO.jpg?raw=true "T4.1 USB Breakout Board - T41U5XBB")

T41E5XBB - Ethernet version
![T4.1 BreakoutBoard](https://github.com/phil-barrett/grbl-teensy-4/blob/master/R6278738_DxO.jpg?raw=true "T4.1 Ethernet BreakoutBoard - T41E5XBB")

Lots of new features!
## Features
  * 5 Axis control outputs – 5V compatible.
  * Independent enables for each axis.
  * 10 Opto-isolated inputs including standard GRBL controls and limits switches for all axes.
  * 7 Relay Outputs – Spindle, Mist Coolant, Flood Coolant, Dust Collector and 3 auxiliary relays. Each output can control a relay coil directly or 5V TTL (SSR compatible) devices.
  * Dust Extraction relay support. Activated by spindle enable.
  * Separate control of Dust Collector relay via pin header.
  * Relay coil voltage switchable between 5V and 12V. 
  * Standard GRBL spindle control outputs – 5V compliant.
  * 0-10V spindle control output.
  * Screw Terminals for reliable connections available for most I/O.
  * 4 Digital Inputs – EMI protected, 15.9KHz low pass filter, Schmitt Trigger.
  * I2C header.
  * EEPROM footprint for SOIC8 devices.
  * LED indicators for 5V and 12V.
  * USB interface.
  * Ethernet interface. (T41E5XBB only)
  * Serial I/O Header

## Documentation
### Schematic
The two versions currently share a common schematic and PCB layout. This may not be the case in the future. [Schematic is here.](https://github.com/phil-barrett/grbl-teensy-4/blob/master/v2.07%20schematic.pdf)

### Manual
Currently being edited. Contains assembly instructions for the "Unkit" version and Bill of Materials. Check back here for availability.

### OSHPark PCB
[Available here](https://oshpark.com/shared_projects/QWr3OZUe)

### Gerbers
[Gerbers are available here.](https://github.com/phil-barrett/grbl-teensy-4/blob/master/teensy%204.1x207.zip)


## Previous Version
![T4 Breakout Board](https://github.com/phil-barrett/grbl-teensy-4/blob/master/PCB%20V100.jpg?raw=true "T4 Breakout Board")

## Features:
  * 4 Axis control outputs – 5V Compatible.
  * 8 Opto-isolated inputs.
  * Full spindle control outputs – 5V compatible.
  * 0-10V spindle control output.
  * 7 Relay Outputs.
  * Relay voltage switchable between 5V and 12V. 
  * Dust Extraction relay output slaved to spindle.
  * Screw Terminal I/O for reliable connections.
  * I2C header.
  * EEPROM footprint for SOIC8 devices.
  * LED indicators for 5V and 12V.
