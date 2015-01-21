# uNAV PCB
**The first DC motor board in 4cm X 4cm** - PCB boards for uNAV 

###Join on open firmware project [uNAV.X](https://github.com/officinerobotiche/uNAV.X)!!!

![uNAVPCB top](https://github.com/officinerobotiche/uNAVPCB/blob/master/Image/preview_Top.png)

# Hardware features
- 2 DC motor control (encoder and H-bridge are required)
- size: 4cm x 4cm
- Breadboard compliant
- Free 256Kb EEPROM in I2C 
- Voltage input 23V
- 4 LEDs
- ICSP programming

## DC Motor control input
- 2 PWM for motor
- Encoder input. *You can select 5V input or 3.3V to power on your encoders*: 
  - 2 channels (A, B)
  - 3 channels (A, B and Z axis)
- Analog input for current sense
- Analog input for temperature sense
- Pin for enable H-Bridge

## Communications
- 2 serial ports
- 1 I2C port
- 7 GP I/O (You can add feature with use remappable pins) 
