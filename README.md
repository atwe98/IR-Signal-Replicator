# IR-Signal-Replicator
An IR remote that can receive and replicate IR signals.
A small project done by me back in high school to get myself familiar with IR signals.

The project uses an Arduino Uno connected to an IR Led, Ir receiver and a single button to be able to receive and send IR signals.

The circuit is always receiving IR signals and saving them to the EEPROM for permanent storage. When the button is pressed, the arduino sends the saved signal.

Library used for IR commands with arduino: [Arduino IRremote](https://github.com/z3t0/Arduino-IRremote) by Ken Shirriff
