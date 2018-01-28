# Savant-Arduino-Relay
Savant Profile to control 8 Arduino digital output pins.
## Synopsis
This Savant profile reads and writes digital pin states to the Arduino via RS-232. You must use a TTL to RS-232 converter connected to pins 0 and 1 of the Arduino for proper serial communication to the Savant controller.
The profile will read a pin's state whenever a write command is sent and will also poll the Arduino for changes every 30 seconds. The Arduino sketch is based on a walkthrough provided below with changes to the way reading of pin states is controlled via serial commands.
http://forums.trossenrobotics.com/tutorials/how-to-diy-128/complete-control-of-an-arduino-via-serial-3300/
## Preparation
STEP 1: Install Arduino Sketch to Arduino via USB

STEP 2:
