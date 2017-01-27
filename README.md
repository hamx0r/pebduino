# pebduino
Pebble UI for Arduino

The goal of this project is to provide a generic interface for an Ardunio where, instead of using 3 buttons and a display, one just uses a bluetooth module to connect an Arduino to a Pebble.

This connection happens directly between an Arduino and a Pebble over Bluetooth - there is no smartphone required.  This will mean, however, that the Pebble bluetooth address be hardcoded into the Aruino code so that it can pair with the desired Pebble.

The code for this project comes in two parts
## Pebble
The Pebble app can also be downloaded and installed just like any normal Pebble app by searching for the Pebduino app.  You can also build what's in the `/pebble/` location and install the pbw file yourself.

## Arduino
The Arhuino code is a library to be used with your Arduino project to route output text and take input from up to 3 buttons (Up, Select, Down). 
