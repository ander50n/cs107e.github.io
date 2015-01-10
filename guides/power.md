## Powering the Raspberry Pi A+ and B+

*Written by Pat Hanrahan*

**Warning: This guide applies to the models A+ and B+, and not A and B*

### Powering using usb connected to a laptop

The simplest way to power the Raspberry Pi is with a micro-usb
cable connected to a usb port on a laptop.

![Mac usb](images/power.usb.laptop.jpg)

Note that there are different types of usb connectors.
The Raspberry Pi uses a micro-usb connector.

Note also that there is also a large USB port.
The large usb connector is not used to power the Pi.

Raspberry Pi A+ does not need much power. 

![Mac usb](images/power.jpg)

A usb port supples 5V and up too 500 mA.
Simple test using an inline power meter shows that the usb
port has a voltage of 4.72V, is suppling 80 mA of current,
and the total power requirement is 0.37 W. That is not a lot
of power! 

Note, however, that the power used 
may go up if you are using LEDs and other peripherals.

### Powering using the usb serial break out board

Another common way to power the Pi is to use the usb
serial break out board.
The header on the break out board has pins for 5V and GND.
These are connected to the Raspberry Pi's GPIO pins as shown.

![usb serial cable](images/power.usb.serial.jpg)

Be careful that you connect things up properly.
For reference, here is a snapshot of the relevant
part of the schematic.

![gpio schematic](images/gpio.schematic.jpg)

### Powering using the micro-usb cable connected to an AC adapter

You can also directly power it with a AC adapter. 
The same kind that you use to charge your phone..

![micro-usb ac-adater](images/power.usb.ac.adapter.jpg)





