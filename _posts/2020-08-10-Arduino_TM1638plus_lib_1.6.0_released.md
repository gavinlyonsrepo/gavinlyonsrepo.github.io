---
layout: post
title:  "Arduino library Tm1638plus version 1.6.0 released"
categories: [cpp, arduino]
---

* Version  1.6.0 August 2020
	* Pull request by [centic9](https://github.com/centic9) Model 1 constructor duplicate code removed.
	* Closed  Issue 1 and 2 on github by adding support for high frequency MCU, such as ESP32
	The constructor of all models has a new parameter if set to true the code uses a custom  "shiftin" function
	* Closed Issue 8 on github, LKM1638 bi-colour LED module support added (named Model 3 for purposes of library )
	* Added support for "Model 3". 
	* New function "setLEDs" added to turn on all LEDs at once, for model 1 and 3.
	* Tested on STM32 "blue pill", it Works!

[Library for TM1638 module Link.](https://github.com/gavinlyonsrepo/TM1638plus)
