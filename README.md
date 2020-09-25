# PlusD Clone 1.4

ZX PlusD clone for all ZX Spectrum computers.

# September 25, 2020

* In this version the solder pads to select the READY signal has been removed.
* Now you can fin a connector of 4x2 pins to put the jumpers.
     
     * Upper row: Cable selector (AT or Shugart)
     * Bottom row: READY signal selector, REAL or EMU
      
     See attached pictures.

# July 27, 2020

Tested & working 100%
* In this version of the board the IC 7805 has been removed. The interface power is taken from the + 5V line of the expansion bus.

# July 11, 2020

* Corrected footprint of U2 (W27E257)
* Everything seems to be OK. Ordering 5 PCB's to test.

# July 6, 2020

* Added a SPDT switch ON-ON to select between ZX 48K/128K & +2A/+3
* Inversion of Drive 1 and Drive 2 now is made by a DPDT Switch (ABBA)
* Now the IC12 (L7805) can be placed horizontally
* Relocation of LEDS, NMI and RESET pushbuttons and some IC's
* Added three 3M holes (3.5mm) to facilitate the fixation on a case
* Kempston Joystick connector now is horizontal
* Changed the DIP switch for ROM selection and Joystick ON-OFF for a DIP Switch Piano style.
* Electrolytic capacitors are now SMD

# Notes

* Based on the designs by @Pachuquin & @alvaroalea

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

* https://www.winuaespanol.com/phpbb3/viewtopic.php?p=7182#p7182
* https://github.com/alvaroalea/plusD-clone
* https://www.va-de-retro.com/foros/viewtopic.php?f=63&t=5561


