# aSysBus - The Arduino System Bus

aSysBus is hard- and software to build a network of arduino nodes using a CAN-bus or other interfaces. It was build as a replacement for [iSysBus<sup>(DE)</sup>](https://www.mikrocontroller.net/articles/Hausbus_Diskussion), which used native AVR code and a java based configuration framework instead of Arduino. It is mostly used for home automation and other control communication.

For CAN communication [Seeed-Studio/CAN_BUS_Shield](https://github.com/Seeed-Studio/CAN_BUS_Shield) is required. 
I forked the Seed Studio Library to support the other Crystal speeds as well. The new CAN-BUS-Shield library will also appear on GitHub.
