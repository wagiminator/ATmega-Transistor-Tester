avrdude -c usbasp -p m328p -U lfuse:w:0xff:m -U hfuse:w:0xdb:m -U efuse:w:0xfd:m
avrdude -c usbasp -p m328p -U flash:w:TransistorTester.hex
avrdude -c usbasp -p m328p -U eeprom:w:TransistorTester.eep

For original source code and more information visit: 
- https://www.mikrocontroller.net/articles/AVR-Transistortester
- https://github.com/Mikrocontroller-net/transistortester
