# Virtual Com Example

Version: 1.0

## MCUxpresso / Kinetis SDK 2.0 / Teensy 3.5 (K64FX512)

This example is intended to demonstrate programming the Teensy 3.5 (https://www.pjrc.com/teensy/) using MCUxpresso and Kinetis SDK 2.0.  
The Teensy boards are generally intended to be used with the Arduino IDE and Teensyduino libraries.  Many people have expressed interest 
in programming the Teensy series directly (not using the Arduino IDE) and this example is intended to help guide them by providing a 
working starting point.

In order to use the workspace directly, you will need to have your MCUxpresso environment configured - there are many resources on the web 
that can guide this setup.  Since the KSDK libraries are copied into the project, it should also be possible to use this example with other 
toolchains.

## Teensy 3.5 Configuration

As provided this example runs the core system clock at 120MHz.  The USB 48MHz clock is provided by the internal IRC48M clock.
The only pin configured is #D8 (Port C, Pin 5). It is configured as an output pin so that the Teensy on-board LED can be flashed
as a signal that the program is running.

The project is configured to generate a .hex file which must be uploaded to the Teensy using the Teensy Loader.

## MCUxpresso Configuration

I have checked-in all of the MCUxpresso (Eclipse) workspace files to make it easier to import the project and have a working environment. 
As new versions (or if attempting to use an older version) of MCUxpresso are released it may cause issues trying to import the project.

If this occurs you may try deleting the .settings directory and re-importing the project.
This version of MCUxpresso used to generate this project is:

MCUXpresso IDE v10.2.1 [Build 795] [2018-07-25] 
(c) Copyright NXP Semiconductors 2006-18. All rights reserved.

