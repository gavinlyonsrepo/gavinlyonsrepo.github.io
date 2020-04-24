---
layout: post
title:  "rpi_tempmon 2.2-3 released"
categories: python
---

* version 2.2-3 
	* For mail mode, replaced ssmpt with msmtp in mail function.
	* ssmtp had to be replaced as ssmtp is deprecated in RPi [Buster](https://raspberrypi.stackexchange.com/questions/99968/cannot-send-mail-from-buster), 
	* and is considered obsolete, users were reporting issues via mail.
	* Users using mail mode option will have to install and configure msmtp.
	* Details in Readme. 


[Rpi temperature monitor](https://github.com/gavinlyonsrepo/raspberrypi_tempmon)
