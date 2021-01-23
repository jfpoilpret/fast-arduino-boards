I2CBoard
========

This board contains the following I2C devices:
- DS1307 RTC (socket)
- MPU6050 Accelerometer/Gyroscope (socket)
- HMC5883L Compass (socket)
- MCP23008 IO expander with 4 DIP switches and 4 LEDs
- TCA9534 IO expander with 4 DIP switches and 4 LEDs
- VL53L0X ToF laser ranger (socket)

It is connected to an Arduino or MCU board with the following header pins:
- GND
- 5V
- SDA (with/without pullup 4.7K)
- SCL (with/without pullup 4.7K)
- MCP23008 INT
- TCA9534 INT
- TODO

The board also includes sockets for all signals, to make it easy to connect a Digital Analyzer for debugging.

