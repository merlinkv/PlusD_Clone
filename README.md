# Original short description

The PlusD (or +D) was a floppy disk and printer interface for the Sinclair ZX Spectrum home computer, developed as a successor to Miles Gordon Technology's earlier product, the DISCiPLE. It runs the GDOS or Uni-Dos operating systems and you can connect up to two 3.5" floppy drives.

The PlusD will allow you to save all your games and serious software to disc at the touch of a button for reloading at any time in the future. With the fastest load and
save times of any disc system available for the Spectrum, the PLUS D will make your computer grow to meet your needs today and tomorrow! In the software arena, many
leading companies are now producing software that is specifically tailored to the PLUS D. But don't worry - you don't have to buy new software to use the PLUS D!
And if some of your software is Microdrive compatible, so much the better! The PLUS D will add a new dimension to all your existing software, greatly enhancing all
your own programs as well!

# PlusD Clone 1.6

My ZX PlusD clone can be used on all ZX Spectrum computers just using a little switch (you don't need a "fixer" for +2A, +2B or +3 models). Also you can select one of the two ROMs included: GDOS & Uni-Dos (up to four ROMs can be used).

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


