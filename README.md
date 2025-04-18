<!---[![License: MIT](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/justcallmekoko/ESP32Marauder/blob/master/LICENSE)--->
<!---[![Gitter](https://badges.gitter.im/justcallmekoko/ESP32Marauder.png)](https://gitter.im/justcallmekoko/ESP32Marauder)--->
<!---[![Build Status](https://travis-ci.com/justcallmekoko/ESP32Marauder.svg?branch=master)](https://travis-ci.com/justcallmekoko/ESP32Marauder)--->
<!---Shields/Badges https://shields.io/--->

# ESP32 Marauder
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ESP32Marauder/blob/master/pictures/marauder3L.jpg?raw=true" width="300"></p>
<p align="center">
  <b>A suite of WiFi/Bluetooth offensive and defensive tools for the ESP32</b>
  <br><br>
  <a href="https://github.com/justcallmekoko/ESP32Marauder/blob/master/LICENSE"><img alt="License" src="https://img.shields.io/github/license/mashape/apistatus.svg"></a>
  <a href="https://gitter.im/justcallmekoko/ESP32Marauder"><img alt="Gitter" src="https://badges.gitter.im/justcallmekoko/ESP32Marauder.png"/></a>
  <a href="https://github.com/justcallmekoko/ESP32Marauder/releases/latest"><img src="https://img.shields.io/github/downloads/justcallmekoko/ESP32Marauder/total" alt="Downloads"/></a>
  <br>
  <a href="https://twitter.com/intent/follow?screen_name=jcmkyoutube"><img src="https://img.shields.io/twitter/follow/jcmkyoutube?style=social&logo=twitter" alt="Twitter"></a>
  <a href="https://www.instagram.com/just.call.me.koko"><img src="https://img.shields.io/badge/Follow%20Me-Instagram-orange" alt="Instagram"/></a>
  <br><br>
</p>
    
[![Build and Push](https://github.com/justcallmekoko/ESP32Marauder/actions/workflows/build_push.yml/badge.svg)](https://github.com/justcallmekoko/ESP32Marauder/actions/workflows/build_push.yml)

## Want to build your own custom firmware?
 to install already compiled version use the m5burner and search for Marauder m5stickc

[Building Firmware From Source](https://github.com/justcallmekoko/ESP32Marauder/wiki/installing-firmware-from-source)
To compile correctly. When installing the libraries just instead of using the libraries that he gives just use the libraries on the [library.rar](https://github.com/gato001k1/ESP32Marauder-for-m5stickc-non-plus/blob/master/libraries.rar) file. Just decompress the file on a folder and select each folder as a library. On the arduino IDE and select sketch, include library, add .ZIP library then select each library folder that you decompressed.

When downloading the Arduino IDE select the 1.8x versions becuase the new arduino 2x versions donesent support the ESP32 Spiffs Tool.

If you want to compile it yourself for the m5stickc non plus set the values of the #define TFT_WIDTH set the value to 107 and the the #define TFT_HEIGHT to 162 on User_Setup_Marauder_M5stickc.h
then copy everything inside User_Setup_Marauder_M5stickc.h delete everything inside User_Setup.h and then paste it there.
Next copy the 2 files to the TFT_eSPI library folder on the arduino folder inside the documents directory because i am to lazy to try witch of the 2 files to copy xd. 

Library fix credits https://github.com/wh1ter0z/ESP32Marauder

Thanks to https://github.com/kazz2020 from justcallmekoko#434 for adding m5stickcplus2



## Getting Started
Download the [latest release](https://github.com/justcallmekoko/ESP32Marauder/releases/latest) of the firmware.  

Check out the project [wiki](https://github.com/justcallmekoko/ESP32Marauder/wiki) for a full overview of the ESP32 Marauder

# For Sale Now
You can buy the ESP32 Marauder using [this link](https://www.justcallmekokollc.com)
