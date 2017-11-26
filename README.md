# grenade
grenade is my original keyboard project

## Compile
make handwired/grenade:default:dfu

## Programming
avrdude -p atmega32u4 -c avr109 -P /dev/tty.usbmodem1411 -U flash:w:./.build/handwired_grenade_default.hex 
