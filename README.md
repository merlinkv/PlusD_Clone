<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

* This clone is based on Miles Gordon Technology +D and later designs by @Pachuquin & @alvaroalea
* If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* You may not use the material for commercial purposes.
* You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

# PlusD Clone 1.6

ZX PlusD clone for all ZX Spectrum computers.

# November 25, 2020

* The solder pad used to select the floppy drive controller IC has been removed.
The floppy drive controller IC's that can be used are: WD1772-02-00, WD1772-02-02 & VL1772-02PC
* Some minor changes.

# October 16, 2020

* Resistors, capacitors (except the two electrolytics) & diodes now are SMD 1206
* Some minor changes

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

Two types can be used as the IC for floppy disk controller: WD1772 (versions 02-00 and 02-02) and VL1772-02PC.
Unfortunately, they are difficult to find at reasonable prices.

The advantages of this interface over the original are:

* 4 Banks of ROM, so you can swap between G+Dos and Unidos, selectable by dip-switches
* Included Fixed for +2A/+3, so can be used in any ZX Spectrum, selection by switch
* Kempston Joystick Interface included, can be disable by dip-switch
* Reset Button
* Posibility of use crossed or plain floppy cable, and invert Drive 1 and Drive 2, very usefull if you have a Gotek and a real floppy.

# Links

* https://www.winuaespanol.com/phpbb3/viewtopic.php?p=7182#p7182
* https://github.com/alvaroalea/plusD-clone
* https://www.va-de-retro.com/foros/viewtopic.php?f=63&t=5561


