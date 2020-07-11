# PlusD_Clone_MOD 1.2

A MOD of the PlusD clone made by alvaroalea

WORK IN PROGRESS I CAN'T GARANTEE THAT IT WORKS AT THE MOMENT !!

# July 11, 2020

* Corrected footprint of U2 (W27E257)

# July 6, 2020

* Added a SPDT switch ON-ON to select between ZX 48K/128K & +2A/+3
* Inversion of Drive 1 and Drive 2 now is made by a DPDT Switch (ABBA)
* Now the IC12 (L7805) can be placed horizontally
* Relocation of LEDS, NMI and RESET pushbuttons and some IC's
* Added three 3M holes (3.5mm) to facilitate the fixation on a case
* Kempston Joystick connector now is horizontal
* Changed the DIP switch for ROM selection and Joystick ON-OFF for a DIP Switch Piano style.
* Electrolytic capacitors are now SMD


# Original description by alvaroalea

The schematic and PCB for this interface, make in KICAD Including gerber files to direct order, the PCB is less than 10x10cm so it's very cheap. Al BOM for order 10 units is also available, some PCB manufacturer allow to order at same time than PCB Aditionaly ICs and Edge conector is needed.

IC for floppy controler is a dificult to found WD1772, in theory WD1770 can be used as a alternative. Also WD1773, probably can be used, JP4 and JP5 must be changed to allow alternative motor control. The interface has been only tested with WD1772 and VL1772-2PH

The Advantege of this interfaz over the original are:

* 4 Banks of ROM, so you can swap between G+Dos and Unidos, selectable by dip-switches
* Included Fixed for +2A/+3, so can be used in any ZX Spectrum, selection by jumpers
* Kempston Joystick Interface included, can be disable by dip-switch
* Reset Button
* Posibility of use crossed and plain floppy cable, and invert Drive 1 and Drive 2, very usefull if you have a Gotek and a real floppy.

# Links

* https://github.com/alvaroalea/plusD-clone


