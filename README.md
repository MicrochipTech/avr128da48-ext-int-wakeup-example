# AVR128DA48 External Interrupt Wake Up Example

This repository provides an Atmel Studio solution with a bare metal code example for an external interrupt wake up. 

In the main loop, the program starts by entering the CPU in Sleep Mode. When the button is pressed, the CPU wakes up and blinks the LED. After those operations the CPU returns to Sleep Mode.

## Configurations

PC6 - LED0 led on Curiosity Nano board is configured as output pin

PC7 - SW0 button on Curiosity Nano board is configured as input pin with pull-up enable

SLPCTRL - Configured for entering Idle Mode

## Required Tools 

Software: ATMEL Studio and AVR-DA Device Packs

Hardware: AVR128DA48 Curiosity Nano

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
