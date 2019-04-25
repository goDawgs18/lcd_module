# lcd_module
I will be trying out the LCD1602 module for the first time 

I decided to also incorporate using an Ultrasonic Sensor HC-SR04 so that I could use changing values

## Connections

LCD1602  |  Arduino
------------ | -------------
VSS  |  5V
VDD  |  Gnd
V0  |  Vout Resistor
RS  |  D12
RW  |  Gnd
E  |  D11
D0-3  |  nothing
D4  |  D5
D5  |  D4
D6  |  D3
D7  |  D2
A  |  3.3V
K  |  GND

10 Kohm Resistor |  LCD1602
------------ | -------------
Vin  |  3.3 V
GND  |  Gnd
Vout  |  V0 

HC-SR04  |  Arduino
------------ | -------------
GND  |  GND
Vcc  |  5V
Echo  |  D6
Trig  |  D7
