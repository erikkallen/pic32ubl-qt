# Pic32ubl-qt #

This is a port of the Windows MFC PIC32UBL bootloader application which is part of Microchip application note AN1388 (PIC32 Bootloader) to Linux and Mac using Qt, LibSerial, libusb and hidapi. Open the pic32ubl-qt.pro project file from QtCreator and build away. I’ve only tested the USB functionality on 64-bit Linux. If you want to use the UART or Ethernet programming you might get lucky. Same goes for OSX and 32 bit Linux. Good luck!

# Update

This version should compile and run on Ubuntu 17.04 on Qt 5.8

# Packages needed to run on ubuntu

* libboost
* libusb-1.0
* libserial

Install using the following command

    sudo apt install libusb-1.0-0-dev libboost-all-dev libserial-dev


# Links #

AN1388: http://www.microchip.com/stellent/idcplg?IdcService=SS_GET_PAGE&nodeId=1824&appnote=en554836

Qt: http://qt-project.org

LibSerial: http://libserial.sourceforge.net

libusb: http://www.libusb.org

hidapi: http://www.signal11.us/oss/hidapi

Judd Robotics: http://juddrobotics.com
