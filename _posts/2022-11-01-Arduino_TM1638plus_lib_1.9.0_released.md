---
layout: post
title:  "Arduino library Tm1638plus version 1.9.0 released"
categories: [cpp, arduino]
---

* Version 1.9.0 November 2022
	* Change made to Model 1/3 displayHex method as per pull request #19.
	* Right aligned text mode added to (as per pull request #17)
		* Model 1/3,  methods displayIntNum and DisplayDecNumNibble
		* Model  2 , methods DisplayDecNum, DisplayDecNumNibble & DisplayHexNum
		* Previously it was just Left aligned text and added leading zeros.

[Library for TM1638 module Link.](https://github.com/gavinlyonsrepo/TM1638plus)
