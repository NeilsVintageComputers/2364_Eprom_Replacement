# 2364_Eprom_Replacement

These adapters mount a smd eeprom, AT28C64B, on a pcb that fits and plugs into the 24-pin 2364 footprint. It is much narrower than all the other adapters I have seen (only as wide as the 2364 socket) which allows them to fit side by side in closely spaced sockets like in the IBM 5150.

The programming adapters that are required to program the eeprom board have a 28 or 32 pin header to plug into a eprom programmer.

The only difference in the two versions is the number of pins on the programming adapter, one has 32 pins which is the number of pins on the smd version of the AT28C64B, the other has 28 pins which is the number of pins on the dil version of the AT28C64.  
Choose which ever version will suit your eprom programmer, if the programmer supports the 32-pin SMD version build the 32-pin adapter or if it only supports the 28-pin throughhole version then build the 28-pin adapter.

The jumpers on the rear should be OPEN when programming the device, CLOSED for use in normal read mode.
The "A" and "B" (Which is NOT a jumper) on the eeprom board should be connected to "A" and "B" on the programmer board.
