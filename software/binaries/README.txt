avrdude -c usbtiny -p m328p -V -U lfuse:w:0xff:m -U hfuse:w:0xdb:m -U efuse:w:0xfd:m
avrdude -c usbtiny -p m328p -U flash:w:TransistorTester.hex
avrdude -c usbtiny -p m328p -U eeprom:w:TransistorTester.eep

for source code and more information visit https://www.mikrocontroller.net/articles/AVR-Transistortester
