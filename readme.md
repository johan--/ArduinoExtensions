# Arduino Extensions

This package contains additional board definitions & libraries that are not
included in the default installation of the arduino software for various reasons.

Getting these software components from the internet is a bit time consuming.
So I created this installer which automaticaly installs the following components.

Tools tested with Arduino IDE 1.0.6

##Included hardware support

* ATMega328 on Breadbord:
	http://arduino.cc/en/Tutorial/ArduinoToBreadboard
 
* ATTiny44/45/84/85:
	http://hlt.media.mit.edu/?p=1695
 
* ATMega644p & ATMega1284:
	https://code.google.com/p/sanguino/

##Libraries

* TinyWireM & TinyWireS: Wire (I2C / TWI) library for the ATtiny85 (using USI)
	http://playground.arduino.cc/Code/USIi2c

* Debouncing library for Arduino or Wiring
	https://github.com/thomasfredericks/Bounce-Arduino-Wiring/

* PS2Keyboard library (Leonardo compatible)
	https://github.com/yosemitebandit/PS2Keyboard
	http://playground.arduino.cc/Main/PS2Keyboard

* DigitalWriteFast - Interupt safe version
	https://code.google.com/p/digitalwritefast/

* Time Library
	http://www.pjrc.com/teensy/td_libs_Time.html

* DS1307RTC Library
	http://www.pjrc.com/teensy/td_libs_DS1307RTC.html

* MAX7221 & MAX7219 library
	http://playground.arduino.cc/Main/LedControl#Source

##Tools
* Termite: a simple RS232 terminal
	http://www.compuphase.com/software_termite.htm