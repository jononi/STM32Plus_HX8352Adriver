# STM32Plus_Touch Display Manager for STM32F4 MCUs
LCD display: 240x400 with HX8352A driver and ADS7843 compatible touch screen controller
Using STM32PLUS library by Andy Brown: http://andybrown.me.uk/wk/category/stm32plus/ and https://github.com/andysworkshop/stm32plus

this is a tested demo that works on library version 4.0.2

contributions:
1. added a new panel trait to the HX8352A driver that is compatible with the display
2. added calibration settings for the touch screen that are loaded initially. Re-calibration is possible later.

work in progress, next steps:
1. add all the files required by this demo
2. publish description + photos of the hardware I'm using currently for this demo
3. make the demo a starting point for a general touch based application
