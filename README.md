# mavroOBD
Arduino (328P) based OBD port module

The goal of this project it to create an Arduino based OBD port module that can be used to enhance a vehicles capabilites.  For example, if you want door locks to close when moving faster than 5mph or to invoke/emulate certain CANbus buttons automatically at start up.

I have uploaded board designs for an OBD module I puchased from China.  It's a two board design.  Lower board solders to the pins of the OBD module and provides a 12V > 5V power supply.  Headers connect to the top board where the Atmel 328P and Microchip MCP2515 CAN Bus controller with SPI interface and MCP2551 CAN transceiver.

This project is based on an Arduino Uno and SeedStudio CAN shield just miniturized to fit in a OBD module.

The module enclousure was purchased from a company in China called AOTAI Industry Co.<br>
Part #: AOT-130N - ODB Connector with housing<br/>
Website: www.aotsisz.com

--------
License
--------

If you are distributing a modified version of the project, please describe the dates and details of your modifications (as described in section 3.3b of the CERN open hardware license).  If you are using a publicly available repository to track changes (which we encourage), you may simply list the URL of the repository here.

https://github.com/dmavromatis/mavroOBD
