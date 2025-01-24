---
layout: post
title:  "Display_Lib_RPI Version 2.1.0 released"
categories: [cpp, rpi, sbc]
---

* Version 2.1.0 24-01-2025
	* Added support for TM1637 LED module.
	* Added support for vectors, with a template to the print method.
	* Replaced the gll font data with better one, same name.
	* Changed MAX7219 code so it can use same ASCII font as TM163X modules.
	* Abstracted most 'lg' library calls to the common data file.
	* Added Scroll test example for ST7789.
	* Added Sprite function for 16 bit color displays
	* Removed any calls to malloc() & free() from library and examples, 
		use vectors and unique pointers instead.

[Github link to library](https://github.com/gavinlyonsrepo/Display_Lib_RPI)
