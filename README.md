# Inflator V3
## Background
I like four wheel driving. I dislike having to sit in the sun to inflate my tyres manually.

Unfortunately the only option (commercially) is on the order of > $300. That is excessive. It can be cheaper.

## Requirements
* Input Voltage: 6V - 18V (nominal)
* Input Voltage: 4V - 30V (transient)
* Functions:
  - HSD/FET gate drive for compressor control & solenoid activation
  - ESP32 for wireless comms (originally wanted STM32 but decided that I would rather control the pressure from webapp on phone)
  - OLED to display pressure readings
 
