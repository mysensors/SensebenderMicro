# Sensebender Micro

This is a micro sensor module for Mysensors project: http://www.mysensors.org

Designed to run on 2 x AA(A) batteries, depending on how often one would
like to replace the batteries. 

The sensor includes the following peripherals

- Si7021 Temperature / Humidity sensor (Connected to I2C bus)
- Jedec compatible eeprom/flash footprint
- ATSHA204A for authentication
- LED

The following pins are available on headers:

- Powersupply (1.8 -> 3.5V)
- SDA / SCL (I2C bus)
- A0 / A1
- D3 / D4 / D5 / D6 / D7
- 6 pin ISP port
- 8 pin standard NRF24L01+ connector layout
- FTDI header for serial

*Please note*

MAXIMUM allowed supply voltage is 3.5V, anything above this WILL fry both
radio and NRF24 radio module. There is NO voltage regulator on board (To keep
supply current down to a minimum)
