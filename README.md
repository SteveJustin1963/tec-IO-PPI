# tec-IO-PPI

The first IO for the TEC-1 was in TE 14-23 , https://github.com/SteveJustin1963/tec-IO

Jim Roberson spoke about a PPI chip. This concept changes from latches to the intel 8255, with 24 PPI parallel input/output ports. 
He said it was for programming eproms.


make a addon using 24 port PPI 8255, a PPI parallel input / output chip. 
 
 
## Circuit
https://easyeda.com/editor#id=4fd98e28aef24e9f8ccac86fc7e77637

 
 

## References
"Interestingly, I found proof that the TEC-1 actually did support loading and parsing intel HEX files from the PC 
and actually had bi-directional bit-banged comms support at multiple baud rates. Therefore these things can be added to any revision without claims that it defeats the legacy scope of the TEC. Unfortunately, the source code is actually a barebones reconstruction from a disassembler and lacks comments. However, I tend to be able to read assembler as easy as plain English so it should be fun going through it all again. (Should I mention that I'm somewhat dyslexic?) :) I also found code that reminded me that I had plans to replace the EPROM with an EEPROM and so that new monitors could be "flashed" onboard the TEC. No UV eraser or, ahem, screwdriver required. There is code for a 8255 PPI based general purpose EPROM programmer included in the archive. Anyway, I've only glanced at the code so it all awaits a detailed review when I get home. Should be interesting!" (Robertson. Jim 2019)


http://www.cpcwiki.eu/index.php/Z80_PIO

https://au.rs-online.com/web/p/microcontrollers/6259084


 

