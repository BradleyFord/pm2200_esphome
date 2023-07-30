# ESPHome Modbus configuration for Schneider PM2200 (pPM230) series Energy Meter

This was forked from https://github.com/htvekov/iem3155_esphome and then heavily adapted for this version

## RS485 modbus module
* [XY-017](https://www.aliexpress.com/item/1005002863807590.html) 'Noname' AliExpress TTL <--> RS485 module
* Simple, cheap module
* Supports both 3.3 and 5v
* 'No hazzle' module with hardware automatic flow control
![XY-017 TTL/RS485 module](https://github.com/htvekov/iem3155_esphome/blob/main/XY-017.png)

The iEM3155 device also offers some additional interesting features that might be useful for others. Tariff/tariff rates and overload alarm. There's also both a digital input and output port that can be utilized as well.

Check the iEM3155 user manual/technical [datasheet](https://download.schneider-electric.com/files?p_Doc_Ref=DOCA0005EN&p_enDocType=User+guide&p_File_Name=DOCA0005EN-13.pdf) for further info
