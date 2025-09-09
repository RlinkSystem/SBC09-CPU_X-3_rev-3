# SBC09-CPU_X-3_rev-3

Simple SBC design around MC6809 Revision 3

This is the second atemp/test to make a full SBC system based on my old
modem X-3 construction, and keep it simpel.

This was done during Summer holiday 2025.
To test my simple & basic setup, and continue to experiment.

My goal is to have an uncomplex build that is not compact, so:
* not with a few large ICs
* not with PAL/GAL
* and with "many" ICs

So my setup is:
* CPU: MC68B09/HD63C09
* MEM: 7x HM6264ALP-15
* ROM: 2764 eq EPROM / EEPROM
* PTM: MC6840
* ACIA: 2x MC6850
* ACIA: R6551
* PIA: 3x MC6821
* Glue logic:
  * 74HCT04
  * 4x 74HCT138
  * 74HCT4040 Baud Rate
* Test support for USB-TTL-UART
  * CH340E (CH340X)

