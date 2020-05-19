# balthazar
Open-hardware laptop computer modules

# BalthazarKeyboard
Electronic schematic modules as presented at https://balthazar.space/wiki/Balthazar with the main aim for team access
KiCad 5.1.5 files

Balthazar open-hardware laptop - keyboard and touchpad module

The computer keyboard system with microcontroller (for now an 8-bit Atmel built into a small Sparkfun ProMicro board). A normal ISO keyboard layout is used. 

An option is given to test the ability of the microcontroller to handle also the control for PSU board and the touchpad module data transfer to USB. Keypad and touchpad user activities are usually mutually exclusive – so this seems ok. Charger control is active a couple of seconds on startup of the system, so this is also ok. 

In case of some charger error there is a mechanical switch on PSU board to stop charging. In this way three functions would be fulfilled in a single microcontroller – connected to the system IO with one USB.

Keyboard pcb has some dimensions already defined by the LCD's dimensions of 13.3 inch in diagonal: 290mm x 180mm. The width is the most determining factor for the keys raster which is about 17mm – instead of the regular 19mm. 

The keys have some ergonomic solution that gives some additional design touch.  

The keyboard switches are important but are for now very typical low cost membrane switches. A little better solution are the softer (silicone) – but still membrane – switches. The idea is to have a waterproof (silicone) layer over the whole board. The board can then already act as a top cover. The feel of silicone rubber is preferred to that of natural rubber. 
