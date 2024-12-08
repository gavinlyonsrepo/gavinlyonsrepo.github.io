---
layout: post
title:  "Display_Lib_RPI Version 2.0.0 released"
categories: [cpp, rpi, sbc]
---

* Version 2.0.0 05-12-2024
	* Changed low level dependency from 'bcm2835' to 'lgpio', primarily so the library can now work on a raspberry 5
	as 'bcm2835' cannot work on raspberry 5. 'lgpio' works with Linux device driver rather than low level register access of 'bcm2835'
	software should now work on any Linux based Single board computer which has SPI.
	* Changed font system, added some different fonts and font data is now horizontally addressed instead of vertically.
	This facilitates using buffered writes to write font much faster character by character in a frame buffer rather than pixel by pixel.
	In the writeChar method of 16-bit color graphic display.

[Github link to library](https://github.com/gavinlyonsrepo/Display_Lib_RPI)
