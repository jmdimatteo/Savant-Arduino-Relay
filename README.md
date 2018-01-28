# Savant-Arduino-Relay
Savant profile to control 8 Arduino digital pins. Relays connected to these pins can control a variety of on/off or momentary open/close devices.
## Synopsis
This Savant profile reads and writes digital pin states to the Arduino via RS-232. You must use a TTL to RS-232 converter connected to pins 0 and 1 of the Arduino for proper serial communication to the Savant controller. Connect your relays to digital pins 4-11 for control of up to 8 relays. The profile will read a pin's state whenever a write command is sent and will also poll the Arduino for changes every 30 seconds. The Arduino sketch is based on a walkthrough provided below but pin mode has been removed from the read commands and more defined status messages were added to console printing.
http://forums.trossenrobotics.com/tutorials/how-to-diy-128/complete-control-of-an-arduino-via-serial-3300/
## Preparation
STEP 1: Install Arduino Sketch to Arduino via USB

STEP 2: Add profile to Blueprint Library then add to configuration.
