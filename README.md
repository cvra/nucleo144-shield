# CVRA Nucleo144 shield

![assembled PCB](/shield.jpg)

## Requirements list
* Alim en entrée
 - 5V, bus + nucleo + shield (borne à visser)
 - 6V, servo (borne à visser)
* debug connector
* 2x CAN interface with CAN transceiver:
  - 6x Connector for one CAN interface (mounted as needed)
  - 3x Connector for other CAN interface (mounted as needed)
* Interface panel connector (20 pin)
  - 5V, GND (2 pin)
  - 2x CAN for debug (1 for each interface) (4 pin)
  - RGB LED (3 GPIO to control) (3 pin)
  - I/O (11 pin)
* 15x RC-Servo output: connecteur 3pin 2.54mm standard (+,-,signal). use PWM if available and GPIO for the rest (software PWM)
* 2x Encoder connector (5-pin Molex CHA, CHB, CHN, 5V, GND)
(3x Encoder connector if I/O available on MCU)
* Additional connectors (if I/O available on MCU)
  - 1x I2C Molex
  - 1x UART Molex
  - 1x SPI Molex
  - 4x GPIO (with 4x GND) on 2.54mm standard pin holes (no connector)
  - 1x 5V power to power board and distribute over CAN
* SDCard/SPI-flash for logging
* Mechanical dimension
  - Width and length, max same as Nucleo-144 board (70mmx108mm)
  - Maximum mechanical available space including output cable for Nucleo board and shield ( height = 36mm, lenght = 136.5mm)

