# OTGW-hc3
OpenTherm Gateway plugin for Fibaro HC3 made as a QuickApp.
This plugin will connect directly from the HC3 to the OTGW device over TCP/IP.

- OTGW product: https://otgw.tclcode.com/
- Fibaro HC3 product: https://www.fibaro.com/nl/products/home-center-3/

The QuickApp will automatically create the following child devices:
- Temperature device: The actual measured temperature of the Thermostat
- Thermostat device: The actual setpoint from the room thermostat is show. Also new setpoint can be set on this device.

## Installation
Access the web interface of the Fibaro HC3 and go to setting and then devices.
Add a new device as shown in the picture below and upload the QuickApp. Use the required file "OtgwCore.fqa".

<img src="https://github.com/EggensEng/OTGW-hc3/blob/main/images/Upload.png?raw=true">

## Configuration
After installation the correct IP and Port settings need to be set.
Below 2 images will show how to edit the required variables and set them to the correct value:

<img src="https://github.com/EggensEng/OTGW-hc3/blob/main/images/SetIpPort.png?raw=true">

<img src="https://github.com/EggensEng/OTGW-hc3/blob/main/images/SetIpPort2.png?raw=true">

