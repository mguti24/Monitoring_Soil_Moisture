# Monitoring_Soil_Moisture
Arduino/c++  code to monitor soil moisture, and irrigate based on moisture.
Instructions:

:Author: mguti24
:Email:
:Date: 01/04/2023
:Revision: version#
:License: Public Domain

= Project: {Project}

Monitoring Soil Moisture using Internet of Things
Device used for comparing irrigation based on moisture and manual irrigation.
Main irrigation based on moisture (smart irrigation is done through this program)

== Step 1: Installation
Install "thing.Properties.h" from the repository and  make sure you have other 
libraries like <DHT_esp.h> and <ArduinoIoTCloud.h> and <Arduino_ConnectionHandler.h>

For example:

This file is made to be used in Arduino cloud and to be operated through the cloud
with the variable for  MoistureThreshold being controlled with the Arduino Dashboard
although the code can be altered to be used locally and not upload data to the cloud 
or even be used with another cloud provider, in such case variables need to be 
defined in the main code and the thingProperties.h file can be ignored

== Step 2: Assemble the circuit

An example device is shown in the picture, with compinent in place with the setup and
two plants, another file is shown in the repo with the system architecture

== Step 3: Load the code

Upload the code contained in this sketch on to your board


=== BOM
Bill of Materials:

Component	Quantity	Supplier	Price / unit
NodeMCU ESP 32S	1	HiLetGo	£8.99
NodeMCU ESP8266	1	AZ Delivery	£3.99
Breadboard	1	AZ Delivery	£3.50
GETIHU Power Bank [2 Pack]	1	Amazon	£22.99
HW390 Soil Moisture Sensor	2	The PiHut	£4.00
DHT 11 Sensor	1	Seeed Studio	£6.30
Water Pump	1	Amazon	£6.99
Silicon Tube 8x10x1000mm	1	Amazon	£4.99
Water Level Sensor	1	Amazon	£4.99
Jumper Wires Pack	1	DFRobot	£3.00
HKE Relay 12V	1	DFRobot	£1.80
Arduino IoT Cloud (Maker)	2 months	Arduino	£5.99 (monthly)
TOTAL			£87.43


=== Help
This document is written in the _AsciiDoc_ format, a markup language to describe documents. 
If you need help you can search the http://www.methods.co.nz/asciidoc[AsciiDoc homepage]
or consult the http://powerman.name/doc/asciidoc[AsciiDoc cheatsheet]

