# Balthazar

Open-hardware laptop computer modules description and concept.

These are electronic schematic modules as presented at https://balthazar.space/wiki/Balthazar with the main aim for team access. See the [main repository](https://github.com/balthazar-space/balthazar) for other designs.

# Balthazar Keyboard
Keyboard and touchpad module - computer keyboard system with microcontroller (for now an 8-bit Atmel built into a small Sparkfun ProMicro board). A normal ISO keyboard layout is used. 

An option is given to test the ability of the microcontroller to handle also the control for PSU board and the touchpad module data transfer to USB. Keypad and touchpad user activities are usually mutually exclusive – so this seems ok. Charger control is active a couple of seconds on startup of the system, so this is also ok. 

In case of some charger error there is a mechanical switch on PSU board to stop charging. In this way three functions would be fulfilled in a single microcontroller – connected to the system IO with one USB.

Keyboard pcb has some dimensions already defined by the LCD's dimensions of 13.3 inch in diagonal: 290mm x 180mm. The width is the most determining factor for the keys raster which is about 17mm – instead of the regular 19mm. 

The keys have some ergonomic solution that gives some additional design touch.  

The keyboard switches are important but are for now very typical low cost membrane switches. A little better solution are the softer (silicone) – but still membrane – switches. The idea is to have a waterproof (silicone) layer over the whole board. The board can then already act as a top cover. The feel of silicone rubber is preferred to that of natural rubber. 

However, this is not finite, and we are pusing to try to deliver the best option.

KiCad files are in version 5.1.5 format.

## Funding

This project is funded through the [NGI Zero Entrust Fund](https://nlnet.nl/entrust), a fund
established by [NLnet](https://nlnet.nl) with financial support from the European Commission's
[Next Generation Internet](https://ngi.eu) program. Learn more on the [NLnet project page](https://nlnet.nl/project/Balthazar-Casing/).

[<img src="https://nlnet.nl/logo/banner.png" alt="NLNet foundation logo" width="300" />](https://nlnet.nl)
[<img src="https://nlnet.nl/image/logos/NGI0Entrust_tag.svg" alt="NGI0 Entrust Logo" width="300" />](https://nlnet.nl/entrust)
