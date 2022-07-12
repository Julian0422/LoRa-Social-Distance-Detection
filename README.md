LoRa Social Distance Detection

Please keep enough social distance from others!
Today, I will share a LoRa project, the LoRa Social Distance Detection.
During the COVID-19, have you kept enough social distance from others?
The device is designed to maintain a social distance of 1.5 meters from others. People who are wearing the device get closer to 1.5 meters, a red LED lights up.

![Picture1](https://user-images.githubusercontent.com/106225286/178451963-b2bc69b2-ee93-4556-85c5-332b5b225162.png)

The project aims to measure the Received Signal Strength Indication (RSSI) value and estimate the distance between the LoRa transceivers. The LoRa transceiver continuously sends and receives data to check the RSSI value from other transceivers. If the estimated distance exceeds 1.5m, the LED will light up.

Hardware Part
This project uses an Arduino Nano 33 IOT and an Adafruit RFM96W LoRa module.

To make it wearable, I also used a 3.7V, 1200mAh Lithium polymer battery as the power source, Microchip MCP73832 IC for charging the Lithium polymer battery, 
and Texas Instruments LMR62421XMFE/NOPB to step up the voltage to 5V to the Arduino Nano 33 IOT.

![Picture2](https://user-images.githubusercontent.com/106225286/178451435-48808f5e-77b3-4659-a92e-465a141c598d.png)

![Picture3](https://user-images.githubusercontent.com/106225286/178451956-1b3cf472-6d32-401d-90e2-cafc7ee6f64a.png)

If you don’t want to do too much, you can also use the power bank to power the MCU by the USB port.

![Picture4](https://user-images.githubusercontent.com/106225286/178451957-45c7c0a0-a330-4b8a-a620-f436dd13a6c5.png)

The above schematic diagrams are drawn in DesignSpark PCB 10.0.

![Picture6](https://user-images.githubusercontent.com/106225286/178451960-9e92d798-1700-4bc3-a168-ae727bb647ab.png)
