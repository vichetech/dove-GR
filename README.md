dove-GR Develop Board([wiki][wiki])
======

Low-cost GNSS Receiver


### Features

* Communication method : BlueTooth, USB
* Supported GNSS signals : L1 GPS/SBAS C/A , L1 GLONASS CT, L1 GALILEO/COMPASS OS Data+Pilot
* Number of channels : 32 channels
* Update rate : Up to 10Hz
* NMEA/BINR protocol commands
* RF Connector : SMA ( External Active/Passive Antenna )

### BlueTooth
* Class 2
* Bluetooth V2.0+EDR
* Serial Port Profile
* Baud Rates : 1200bps to 900Kbps

### USB
* USB to UART
* Virtual COM Port Devices Drivers(Windows, Mac OS-X, Linux)
* Baud Rates : 300bps to 2.0Mbps

### Purpose of Use
* Android : [RtkGps Application][rtkgps]
* Desktop : [Rtklib][rtklib]

### Related Data
* dove-GR Description : [dove-GR_Description.pdf][description]
* dove-GR Schematic : [Schematic][schematic]
* dove-GR Dimension : [Dimension][dimension]
* dove-GR RTKLib : [dove-GR RTKNavi Manual][naviM]
* dove-GR RtkGps : [dove-GR RtkGps Manual][rtkgpsM]
* GPS Module datasheet : [NV08C_CSM_DS_v2_4_ENG.pdf][nv08c]
* Bluetooth datasheet : [BCD210.pdf][bcd210]
* USB to Serial Driver : [USB Driver]
![dove_GR : Low-cost GNSS Receiver][image]

[wiki]: http://vichetech.com/wiki
[rtklib]: http://www.rtklib.com/ 
[rtkgps]: https://github.com/vichetech/RtkGps
[image]: https://raw.github.com/vichetech/dove-GR/master/CAM01206.jpg
[description]: https://raw.github.com/vichetech/dove-GR/master/Dove-GR_Description.pdf
[nv08c]: https://raw.github.com/vichetech/dove-GR/master/NV08C_CSM_DS_v2_4_ENG.pdf
[bcd210]: https://raw.github.com/vichetech/dove-GR/master/ds_Parani-BCD210_v1.0.0_kr.pdf
[USB Driver]:http://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx
[schematic]:https://raw.github.com/vichetech/dove-GR/master/doveGR_Schematic.pdf
[dimension]:https://raw.github.com/vichetech/dove-GR/master/dove-GR_Dimension.jpg
[naviM]:https://raw.github.com/vichetech/dove-GR/master/dove-GR_RTKLib-Navi.pdf
[rtkgpsM]:https://raw.github.com/vichetech/dove-GR/master/RtkGps(AndroidApp)_UserManual.pdf
