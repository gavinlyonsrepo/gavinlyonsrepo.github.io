---
layout: post
title:  "Arduino library BMP280_LTSM created"
categories: [cpp, arduino]
---


* Name: BMP280_LTSM
* Description:

Arduino Library for Bosch BMP280 Digital pressure sensor.

* Supports sensors features:

1. Read pressure data
2. Read temperature data
3. Tested on SPI interface and I2C interface, Interface is selected by user constructor overload(see examples)
4. Oversampling settings, standby times, Filter settings and can be set thru API.
5. Normal mode, sleep mode and forced mode supported.
6. This supports the BMP280 sensor fully only. The humidity functionality of the BME280 is not tested or supported.
7. 3 Examples files 2 for SPI and 1 for I2C.
8. Chip ID should be 0x56-0X58 for BMP280, 0x60 BME280. 
9. Hardware SPI and I2C supported.


[Github Link.](https://github.com/gavinlyonsrepo/BMP280_LTSM)
