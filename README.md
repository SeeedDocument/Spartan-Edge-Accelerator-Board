---
name: Spartan Edge Accelerator Board
category: Platform
bzurl: 
oldwikiname: 
prodimagename:
surveyurl: 
sku: 102030005
tags:
---

![](https://github.com/SeeedDocument/Spartan-Edge-Accelerator-Board/raw/master/img/Spartan-Edge-Accelerater-Board-v1.0-wiki.jpg)



The Spartan Edge Accelerator Board (SEA Board in short) is a lightweight FPGA development board, it is based on the Xilinx Spartan-7 chip and follows the Arduino shield form factor. Hence, you can use it as an Arduino shield to driver an LCD and a camera or as a stand-alone FPGA development board. Besides, with the help of on-board ESP32 chip, the SEA board also enables your Arduino with WiFi and Bluetooth function.



**Spartan-7** is the newest and most cost-effective FPGA chip among Xilinx’s FPGA family, offers the best in class performance per watt. 


On top of that, we provide the full FPGA APIs for Arduino, which means Arduino users are able to use the FPGA function without knowing anything about FPGA. This board will broaden Arduino’s capability in many ways like simple image processing and computer vision application, signal encryption and decryption, and signal sampling and processing. 



## Features

- Full FPGA APIs for Arduino
- Stand alone mode/Arduino Shield mode
- On-board WiFi and bluetooth 4.1 with BLE
- On-board 8 bit ADC
- On-board 6 axis Accelerometer and Gyroscope
- On-board Grove Connector(I2C/D2)



## Specification

|Parameter|Value|
|---|---|
|**FPGA**||
|FPGA Chip|Spartan-7 XC7S15|
|Logic Cells|12,800|
|Slics|2000|
|CLB Flip-Flops|16,000|
|Max. Distributed RAM (Kb)|150|
|Block RAM/FIFO w / ECC (36 kb each)|10|
|Total Block RAM (Kb)|360|
|Clock Mgmt Tiles (1 MMCM + 1 PLL)|2|
|DSP Slices|20|
|**Wireless**||
|Wireless Chip|Espressif ESP32-D0WDQ6|
|WiFi |802.11 b/g/n 2.4GHz|
|Bluetooth|Bluetooth 4.1 with BLE|
|**Peripheral**||
|Video|Mini HDMI x1|
|Camera|CSI/MIPI interface x1 (compatible with Raspberry Pi Camera V1 - OV5640)|
|SD card|Micro SD/TF card slot x1|
|FPGA GPIO|10 pins header (IO9~IO0)|
|Arduino GPIO|32 pins header (Arduino form factor)|
|Grove|Grove Connector x2 (I2C/D2)|
|LED|Monochrome LED x2<br>RGB LED x2|
|Button|Boot x1<br> Reset x1<br> FPGA Reset x1 <br> User x2|
|Switch|Power Mode Switch x1<br>5-Channel DIP Switch x1|
|**Power**||
|Operating Voltage|5V|
|Power Mode|USB Type C 5V<br>VIN 5V<br>Arduino VCC 5V|
|**Others**||
|ADC|8 bit ADC1173|
|Accelerometer and Gyroscope|6-axis LSM6DS3TR |






## Hardware Overview


<div align="center">
<figure>
  <a href="https://raw.githubusercontent.com/SeeedDocument/Spartan-Edge-Accelerator-Board/master/img/Spartan-Edge-Accelerater-Board-v1.0-pin.jpg" target="_blank"><img src="https://github.com/SeeedDocument/Spartan-Edge-Accelerator-Board/raw/master/img/Spartan-Edge-Accelerater-Board-v1.0-pin.jpg" alt="Seeed relay quick selection diagram" title="Seeed relay quick selection diagram" />
  <figcaption><b>Figure 1</b>. <i>Seeed relay quick selection diagram, you can click the diagram to view the original file</i></figcaption></a>
</figure>
</div>



|Number|Detail|
|-----|-------|
|1.|FPGA : XC7S15-1FTGB196C|
|2.|WiFi/Bluetooth : ESP32-D0WDQ6|
|3.|6-axis Accelerometer and Gyroscope : LSM6DS3TR |
|4.|DAC : DAC7311IDCKR|
|5.|Buck-DCDC : TPS62130|
|6.|USB-to-UART : CP2102-GMR|
|7.|USB : Type-C |
|8.|Mini HDMI|
|9.|CSI Interface ：MIPI Camera (compatible with Raspberry Pi Camera V1 - OV5640)|
|10.|Arduino Header : Compatible with Arduino UNO|
|11.|DIP Switchs :|K1-K4 user switchs<br>K5 Switch FPGA Programming Mode  ->JTAG:|
|12.||





 






based on Spartan-7, one of the newest and most cost-effective chip among Xilinx’s FPGA family. 









<p style=":center"><a href="https://www.seeedstudio.com/Wio-Lite-MG126-p-4189.html" target="_blank"><img src="https://github.com/SeeedDocument/wiki_english/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png" /></a></p>