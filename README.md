# 82S100replacement
A CPLD implementation of the classic 82S100/82S101 as used in for example C64

![82S100 replacement](http://i.imgur.com/77l1N92.png)

The WinCUPL code is taken directly from the VHDL made by Thomas 'skoe' Giesel and simply translated into WinCUPL. Skoe made an excellent [description](http://skoe.de/docs/c64-dissected/pla/c64_pla_dissected_r1.1_a4ds.pdf) on the C64 PLA which is very well worth reading.

Yes. I am aware that I did a small mistake in that the JTAG connector doesn't have 0.1" pitch.

![In C64](http://i.imgur.com/hFkUcB3l.jpg)

Compared with other C64 PLA replacements this one is more generic 82S100 or 82S101 replacement since the #OE signal is provided at pin 19 and there is no special buffering on the outputs so they can be either tristate or open collector as the designer of the WinCUPL file wishes.
