# SAMG55_oxyboard
\simple Board designed for the SAMG55 Atmel microprocessor

Board designed for the elective subject "Introduction to printed circuit Design" of the Electronic Engineering Degree on Universidad Tecnológica Nacional Facultad Regional Buenos Aires (UTN-FRBA). 

The developed board was designed to have a SAMG55J19 Atmel Microcontroller, which will be capable of receiving the information by a I2C sensor, show the obtained information to the user (using a small LCD display) and be able to send it though a wireless communication, using a WiFi module, to a third-party or a database. This project does not have the sensor incorporated in it, it is on another board which is mounted under it.
The  Wi-Fi transceiver used was the RN1810E, from Microchip. It has a UART interface, and the module already has the antena integrated.  
It has a BQ21040 battery charger and a BU33SD5WG-TR regulator, since this will be a LiOn battery source board. The battery has to be charged through a MicroUSB. 
