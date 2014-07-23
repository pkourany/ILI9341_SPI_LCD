ILI9341 SPI LCD Library
====================== 

Library for ILI9341 low cost SPI LCD displays.

Requirements
------------
Adafruit_mfGFX library


Usage
-----

Hardware SPI is used:

 A2 : SS(Slave Select)
 
 A3 : SCK(Serial Clock)
 
 A4 : MISO(Master In Slave Out)
 
 A5 : MOSI(Master Out Slave In)

Constructor:

  Adafruit_ILI9341 display(uint8_t cs, uint8_t dc, uint8_t rst)
  
	cs - Chip select (aka slave select)
	dc - D/C or A0 on the unit (Data/command select)
	rst - Reset
