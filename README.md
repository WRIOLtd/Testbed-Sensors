# Testbed-Sensors

This app is build for TARGET=zoul and BOARD=remote-revb, it could easily be compiled and burn to /dev/ttyUSB0 Mote with fillowing command:

make TARGET=zoul BOARD=remote-revb MOTES=/dev/ttyUSB0 toggle-shell.upload

After running the app in controller, it waits for User query from serial and response accordingly