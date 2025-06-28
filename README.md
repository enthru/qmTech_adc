# redQmtech_notes_adc

LTC2208 ADC module for DIY HF receiver/transceiver.

**I'm not an electronics/rf proffesional so design is non optimal, has a space to improve e.t.c.**<br>
<br>
It has LPF in the input- cutoff frequency is around 60MHz. 
<br>
RD/RE - use 0 resistor to disable or enable randomizer.
<br>
<br>

With my project for QMTech module it has not good IMD3 DR for this ADC - around 70dbFS, I think it because of traces (designed for LVDS mode) on the QMTech module,
but also can be partially caused by design of this ADC board.
<br><br>
Github for Xilinx bitstream - https://github.com/enthru/redQmtech_notes
<br>
Some history of the project - https://enthru.net/?tag=qmtech
