# I2C-Playground

Small repository to document different uses of I2C GPIO pins. Purely educational for the purpose of learning how to configure and use I2C and to learn their difference with normal Arduino pins.

>Challenge 1: Input pins\
>Goal:
Treating IOA as input (via pushbutton or other means),
Turn IOB output LED on when a push is detected via read() functionality
base code taken from-> https://github.com/adafruit/Adafruit_Learning_System_Guides/blob/master/Adafruit_DS2413/DS2413/DS2413.ino\

>Material:
Adafruit DS2413
Arduino Uno
Header pins
Mini breadboard
Jumper wires
Usb to USB blaster cable
1x LED
1x pushbutton
1x 1k Ohm resister
1x 4.7k Ohm resister as pull-up resistor (only 1 is needed even if multiple DS2413 are used)
5V battery (Optional for computer free operation)
