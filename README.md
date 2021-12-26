# Please note: this project is work in progress and isn't a finished product

This project is licensed under "CERN Open Hardware v2 - Permissive" or "CERN-OHL-P" license, please refer to the [LICENSE](LICENSE) for more details.
When referring to or using hardware sources or finished design files provided here, you must comply with the license terms.


## Description

__Dead Kings__ is a bass or guitar effect pedal consisting of mixable clean and distortion channels. It is built using mostly germanium transistors as active amplification devices. Its power supply is a standard 9V DC with center-negative 5.2 mm barrel connector, commonly used in most guitar pedals. It is possible to power it from a 9V battery but not recommended due to moderate to high current draw.

This device is designed as set of separate modules that can be used on their own.
The following modules are under development now:

* High-impedance buffer with variable gain
* 2 band EQ, inspired by Max Robinson's https://www.angelfire.com/electronic/funwithtubes/Amp-Tone-A.html 

## Source repository folder structure: 

* /design/ - various design files - for example drawings, charts and block diagrams
* /kicad/ - hardware design source and output files made in Kicad EDA 
* /sim/ - Spice circuit simulations made in LTSpice  

## TODO

* Move from LTSpice to Spectrum Micro-Cap?
* Work on octaver Fuzz module
* Work on everdrive module
* Work on mixer module
