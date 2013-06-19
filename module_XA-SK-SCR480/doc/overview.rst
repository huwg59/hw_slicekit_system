sliceCARD overview
===================

Pack contents
-------------

   * One XA-SK-SCR480 sliceCARD
   * One Kentec K430WQA-V4-F 480x272 color resistive touch screen with cable

Parallel RGB565
---------------

This slice provides power supply electronics and a 40-pin ZIF connector for the 
included LCD, plus a low cost resistive touch screen controller that interfaces 
to the LCD and the XCore via a 2-wire interface. The touch functionality is only 
accessible when the slice is placed in the TRIANGLE slot.

The parallel RGB interface is driven directly from the xSOFTip LCD controller 
component running on the xCORE using 1 x 16-bit port and 4 x 1-bit ports. The 
xSOFTip LCD controller is capable of driving screens with resolutions up to 
800x600 (in conjunction with the XA-SK-SDRAM sliceCARD and xSOFTip SDRAM controller component). 

Resistive touch controller
--------------------------

An Analog Devices touch screen controller ADC is provided on the sliceCARD and 
interfaced to the xCORE via an I2C bus and an interrupt line. This can be used 
to provide resistive touch co-ordinate information to software applications written 
for this slice.




