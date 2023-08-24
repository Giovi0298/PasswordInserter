# Configuration Software

The configuration software interacts with the Arduino to enter new passwords or change existing ones and manage the assignment to the relative fingerprints.

## General structure

As mentioned above, the software will interact with the Arduino requesting information about the passwords already present in the EEPROM and to which fingerprint this password is connected.

This information will be displayed in an [interface](#interface) where you can change assignments, passwords and fingerprints.

Everything will be managed by the [backend](#backend) which will communicate with the Arduino via a serial port at 9600bps.

## Interface

## Backend