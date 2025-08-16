# ZMK Firmware for Scylla

This is my personal ZMK firmware for the Scylla keyboard, built with Nice!Nano v2 microcontrollers, and a Seeed Xiao dongle.

## Features

This firmware includes support for a dongle and ZMK Studio.
You can toggle between them by commenting or uncommenting in `build.yaml`.
I haven't tested Bluetooth and ZMK Studio at the same time but I assume it works.

## Usage

To use this firmware for your own Scylla:
Just fork the repository, update the keymap to your needs, go the Actions and download the firmware.
It should work with minimal changes.

## Flashing
Flash the correct reset for each microcontroller. Then turn off the keyboards. Flash dongle firmware, then each half firmware. Then you should be able to turn on the keyboards and it should work.
