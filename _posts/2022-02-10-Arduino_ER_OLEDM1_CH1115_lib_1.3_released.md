---
layout: post
title:  "Arduino library ER_OLEDM1_CH1115 1.3.0 released"
categories: [cpp, arduino]
---

* Version 1.3 Feb 2022
	* drawBitmap() function is now set up for both horizontal and vertical addressed bitmap data,
	 Vertical is default. The addressing mode is changed by setDrawBitmapAddr(), new function.  
	* Enum added for font name labels instead of raw numbers, 
	This will cause font compiler warnings for sketch's written on versions before 1.3.0 , The sketch's will still compile and work,
	Simply replace font numbers  with the relevant enum text labels to get rid of warnings. 
	* A new function added for initialising a multibuffer struct , OLEDinitBufferStruct(),
	backward compatible with old manual workflow.  


* Library for ER-OLEDM1.09-1  , CH1115 controller, [here at github link.](https://github.com/gavinlyonsrepo/ER_OLEDM1_CH1115)

