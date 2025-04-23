# redQmtech_notes_adc

This is the working template/example of the LTC2208 ADC module for DIY HF receiver/transceiver.

**Use only as template or for testing purposes** it won't give you parameters that LTC2208 should.

This is the almost first PCB made by me and the purpose of the board is just to create cheap and simple ADC module for my test transceiver based on the Xilinx QMTech board without spending alot of time. It has non optimal design. 

So consider it as the start point of making your ADC module, because looks like there lot of space to improve.

Anyway it's working. So it's usable.

It has LPF in the input- cutoff frequency is around 60MHz.

**WARNING!**
This board ground near the pinout MUST BE connected to the FPGA board groud near the pinout, I forgot to add ground pin so I scratched mask near pinout and solder ground by wire.

Use R6, R7, R8, R9 resistors to choose output mode of the ADC (check datasheet, but for my project R9 not soldered, R8 = 0R, R7 = 0R, R6 not soldered).

Use R4 and R5 to enable LTC6400IUD driver or bypass it.




Github for Xilinx bitstream - https://github.com/enthru/redQmtech_notes

Some history of the project - https://enthru.net/?tag=qmtech

EasyEDA project of the example ADC board with two LTC2208 - https://oshwlab.com/neuroworker/redqmtechadc
