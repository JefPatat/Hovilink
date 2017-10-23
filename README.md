# Hovilink
**Ho**mebrew **vi**essmann Opto**link** is a serial to network interface built to connect a Viessmann Vitotronic heating control to the network or internet.

# Motivation
I have been using a bulky self built interface based on information available openv together with PC software. This setup was not handy and serious overkill for the purpose. I want to enable myself to communicate with my heater over the network. To keep this flexible the harware is split up in an interface module which translates the optical signals to RS232. This RS232 can then be connected with various other interfaces.

# Limitations
The initial setup of this repository only aims to opensource my personal project and is limited to my personal heater and setup. I'm open to input of the community to expand on this.

# Hardware
The Vitotronic uses an optocoupler to communicate. It uses its status LEDs for this. The left, red, LED functions as an error indicator and at the same time as an infrared receiver. The right, green, LED as an operation indicator an infrared transmitter. Further details will be added to the wiki.

# Software
TBD

# Credits
https://openv.wikispaces.com
