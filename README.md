# aSysBus Beta - The Fork of Arduino System Bus from Adlerweb
Changes in this Beta Release:
Added support for 4MHz, 10MHz, 20MHz Crystals and improved syntax highlighting in Arduino IDE and Platformio

aSysBus is hard- and software to build a network of arduino nodes using a CAN-bus or other interfaces. It was build as a replacement for [iSysBus<sup>(DE)</sup>](https://www.mikrocontroller.net/articles/Hausbus_Diskussion), which used native AVR code and a java based configuration framework instead of Arduino. It is mostly used for home automation and other control communication.

For CAN communication [Seeed-Studio/CAN_BUS_Shield](https://github.com/Seeed-Studio/CAN_BUS_Shield) is required. 
I forked the Seed Studio Library to support the other Crystal speeds as well. The new CAN-BUS-Shield library will also appear on GitHub.
!!!This fork has not yet been tested in terms of hardware, but it will be compiled without errors!!!

For more Information looks the GitHub Wiki from the Original aSysBus Library from Adlerweb [aSysBus Wiki on Github](https://github.com/adlerweb/asysbus/wiki)