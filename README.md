# FastArduino Boards

This project contains several Kicad-based PCB designs that I use for testing FastArduino examples.

Indeed, before releasing a new FastArduino version, I try a lot of the supplied examples in real life, to ensure no regression occurred in the library.

Most of the time spent in these tests is dedicated to wiring, which is boring and a waste of time. It is also error-prone because, if I use a breadboard, I need to open the device datasheets and check each pin; then if I change MCU and need to rework wiring, I need to check pins again.

Thanks to PCBs in this project, I am able to reduce wiring time when I need to perform tests of FastArduino library through examples.

There are several boards, based on several kinds of examples:

1. I2C test board: contains all I2C devices (or connectors to devices breakouts) in order to support testing all I2C devices supported by FastArduino
2. I/O test board: contains buttons, switches, LEDs, pots used for many simple FastArduino I/O examples 
3. NRF24L01 test board: enables to connect 2 SPI NRF24L01 (each on its own MCU/Arduino)

In addition to these boards, I also put other boards that I use often:

1. ATtiny84 MCU board
2. ATtiny85 MCU board
3. TCRT5000 checker board

All Kicad designs try to follow a project organization that makes them stand-alone (symbols and footsprints), as described [here](https://hackaday.com/2017/05/18/kicad-best-practises-library-management/).



