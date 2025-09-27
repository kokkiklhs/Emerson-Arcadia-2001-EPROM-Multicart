# Emerson-Arcadia-2001-EPROM-Multicart
Experimental 8x8KB EPROM cart for the Arcadia 2001 retro console and compatibles, based on 27512.
Simple schematic, easy to build project and at a very low cost. An EPROM programmer is needed in order to feed the 27512 with the games required.
Just chain eight 8KB (8192 bytes long) game files to each other with some suitable utility proggy (e.g. WinHEX editor for Windoze) and burn the resulting 64KB .bin file to a 27512.
I have included a sample 64KB .bin file here, ready to be written on  an empty EPROM.

Games larger than 8KB are NOT supported and in case you want to include game files with size LESS than 8KB each, remember to convert them to 8K by adding some zeros after the end of the game file.
NOTE: This PCB has NOT been tested yet by me on real hardware, but the schematic is correct and the connector size is accurate, so why not give it a try?
