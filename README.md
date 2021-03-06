Welcome to the USB-to-Sero-Controller Interface Project!

This program allows you to control servos from a custom USB device using the 
Python Programming language.  In this case, the hardware interface is a 
Teensy 2.0 Development board.  Theoretically, you can control up to 12 
servos at once from a Python program.

The end goal is to provide the Raspberry Pi with high-level access (via Python)
 to low-level motor control via a hardware interface.

To get started, you'll need a combination of hardware and software before 
being able to run these examples:

### Hardware:
- A Teensy 2.0  
   Source: http://www.pjrc.com/store/teensy.html    
- up to 12 servos connected to digital pins 0 through 13 (but NOT pin 11, the 
LED pin.

### Software:
- PyUSB  
   Source: http://sourceforge.net/apps/trac/pyusb/  
- Arduino 1.0.1 Teensyduino installation  
   Source: http://www.pjrc.com/teensy/teensyduino.html

### Getting Started:
  If you're completely new to servos with Arduino, you might find the link 
below quite handy to overcoming many typical problems:
http://rcarduino.blogspot.com/2012/04/servo-problems-with-arduino-part-1.html
Note, however, that this code snippet MUST be used with a Teensy, not an 
Arduino Uno.  
  To run the examples, simply install the necessary hardware and software, 
upload the Teensy sketch, and run the corresponding Python example.


### Citations:
  Riding on the shoulders of giants, this project would be impossible without
 the incredible starter code provided by Paul Stoffregen found in the examples 
tab under: `File-->Examples-->Teensy-->USB_RawHID-->Basic`.  

Other sources can be found here:  
 - http://stackoverflow.com/questions/8218683/pyusb-cannot-set-configuration  
 - http://www.servocity.com/html/how_do_servos_work_.html  

