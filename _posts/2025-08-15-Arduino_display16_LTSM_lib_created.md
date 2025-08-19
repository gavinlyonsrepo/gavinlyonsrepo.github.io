---
layout: post
title:  "Arduino library display16_LTSM created"
categories: [cpp, arduino]
---


## Overview 

Name: display16_LTSM

Author: Gavin Lyons.

Description:

1. Graphics Library for 16-bit color graphic displays for Arduino eco-system.
2. C++ Library.
3. Graphics class included.
4. Bitmaps supported: 1, 8, and 16 bit + sprites.
5. Multiple displays supported, see supported-devices, new components can be added.
    Device display driver are separate libraries that import this one.
    User can write their own if device not supported.
6. 16 fonts included, new fonts can be easily added without changing source code
7. [URL library github link](https://github.com/gavinlyonsrepo/display16_LTSM)
8. Extensible via separate driver libraries (ILI9341, ST7735, ST7789, SSD1331, GC9A01)


## Supported devices

Component drivers are separate dependent downstream libraries that include this library.

| Component name | Type | Interface | Readme URL link |
| -------- | ---------- | --------- | ---------- |
| ST7735 | TFT LCD|SPI HW & SW| [github link](https://github.com/gavinlyonsrepo/ST7735_LTSM)|
| ST7789 | TFT LCD|SPI HW & SW| [github link](https://github.com/gavinlyonsrepo/ST7789_LTSM)|
| SSD1331| OLED |SPI HW & SW  | [github link](https://github.com/gavinlyonsrepo/SSD1331_LTSM)|
| ILI9341 | TFT LCD |SPI HW & SW  | [github link](https://github.com/gavinlyonsrepo/ILI9341_LTSM)|
| GC9A01 | TFT LCD |SPI HW & SW  | [github link](https://github.com/gavinlyonsrepo/GC9A01_LTSM)|

