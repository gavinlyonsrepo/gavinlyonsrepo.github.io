---
layout: post
title:  "Arduino library Tm1638plus 1.8.0 released"
categories: [cpp, arduino]
---

* Version 1.8.0 November 2021 
	* Minor update.
	* Some users  have reported the high frequency shiftIn function does not work fully with some micro-controller boards at high frequency(ESP32 240Mhz) and the fix is a minor adjustment to sequence in said function. Never saw the issue in my testing. The change makes  the function sequence similar to the official Arduino shiftIn function structure in the Arduino Core (wiring.shift.c) ,  See issue 16 on github issues for more details.
	* Also made uS delay in shiftIn function variable by user..

[Library for TM1638 module Link.](https://github.com/gavinlyonsrepo/TM1638plus)
