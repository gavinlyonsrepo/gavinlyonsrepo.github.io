---
layout: post
title:  "Arduino library Tm1638plus version 1.2.0 released"
categories: cpp
---


* Version 1.2.0 November 2019
	* Patch to deal with issue number 3 on github, dealing 
	with swapped displays on some modules (model 2) with different wiring, See Note A in Readme.md
	* Removed ASCII font to a separate file for efficiency purposes as it was duplicated in both header files.
	* Memory footprint decrease for Model 2 library by using "Progmem" for the ASCII font file data as per Model 1. 


[Library for TM1638 module Link.](https://github.com/gavinlyonsrepo/TM1638plus)
