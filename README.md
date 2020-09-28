# LaserShark
A customized firmware for CNC/3D printers forked from [Marlin](https://github.com/MarlinFirmware/Marlin) 1.1.9.1, specificly tageted towards TTL/PWM driven lasers /w Tech Cooling. ie. 'Endurence Lasers' or other similar products.

As of 0.4.20b LaserShark only supports the 12864 [Full Graphic Smart Controller](https://reprap.org/wiki/RepRapDiscount_Full_Graphic_Smart_Controller) and has only been tested on an MKS 1.4 and a generic RAMPS 1.4, though it could easily be modified slightly to acomodate other boards in future using the same steps taken to configure Marlin.

Take a look in:
                    Configuration.h, 
                    Configuration_adv.h, 
                    pins.h,
                    pins_RAMPS.h (if using RAMPS based boards)
                    along with any other relevant pin files (ie. pins_YOURBOARDHERE)
 
For options and settings, I'll post a "PRECONFIGURED" folder in this repository, for people who arent quite sure what to do, but can copy from examples and just want preconfigured files. Just locate your board folder and drag and drop the files inside into LaserShark directory and overwrite all files when asked. voila. Compile and upload with Arduino IDE  and your off (after adding all required libraries).
  
Please test this out yourself, but please dont expect a fully polished product...yet! It's only been a few days of tinkering and most is just superficial for now, though some cool safty features have been added for lasers.

Please ENJOY and share with the community your creations! Input and recomendations always welcome!

Stay safe and good vibes your way.
bodged together by BuZkill
 
