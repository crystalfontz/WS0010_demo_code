# WS0010 Demonstration Code

Example Seeeduino (Arduino clone) code for the Crystalfontz family of OLED displays that use the WS0010 controller. These displays come in a variety of interface options and colors. 

Below is a full list of parts that we offer that use this controller.

[CFAL0802AY](https://www.crystalfontz.com/product/CFAL0802AY)\
[CFAL1202AY](https://www.crystalfontz.com/product/CFAL1202AY)\
[CFAL1602CB](https://www.crystalfontz.com/product/CFAL1602CB)\
[CFAL1602CG](https://www.crystalfontz.com/product/CFAL1602CG)\
[CFAL1602CGT](https://www.crystalfontz.com/product/CFAL1602CGT)\
[CFAL1602CPW](https://www.crystalfontz.com/product/CFAL1602CPW)\
[CFAL1602CPY](https://www.crystalfontz.com/product/CFAL1602CPY)\
[CFAL1602CPYT](https://www.crystalfontz.com/product/CFAL1602CPYT)\
[CFAL1602CW](https://www.crystalfontz.com/product/CFAL1602CW)\
[CFAL1602CY](https://www.crystalfontz.com/product/CFAL1602CY)\
[CFAL1602CYT](https://www.crystalfontz.com/product/CFAL1602CYT)\
[CFAL1602L0Y](https://www.crystalfontz.com/product/CFAL1602L0Y)\
[CFAL2002AY](https://www.crystalfontz.com/product/CFAL2002AY)\
[CFAL2004AY](https://www.crystalfontz.com/product/CFAL2004AY)\
[CFAL5016APY](https://www.crystalfontz.com/product/CFAL5016APY)\
[CFAL5016AY](https://www.crystalfontz.com/product/CFAL5016AY)\


## Connection Details
##### SPI Configuration
| Display Pin       | Seeeduino Pin | Connection Description            
|-------------------|---------------|-----------------------------------
| GND               | GND           | Ground
| 3v3               | 3v3           | Voltage in
| RES               | D9            | Reset pin
| DNC               | no connect    | Do not connect
| DC (RS)           | D8            | Data or Command Register Select
| CS                | D10           | Chip Select
| RD/E              | DNC           | Read (8080) or Enable (6800)
| WR/RW             | DNC           | Write (9090) or Read/Write (6800)
| D0                | DNC           | Data pin 0
| D1                | DNC           | Data pin 1
| D2                | DNC           | Data pin 2
| D3                | DNC           | Data pin 3
| D4                | DNC           | Data pin 4
| D5                | DNC           | Data pin 5
| D6/CLK            | D13           | Data pin 6 or Clock pin for SPI
| D7/MOSI           | D11           | Data pin 7 or MOSI pin for SPI

#### Parallel Configuration
This code currently only demonstrates using the SPI interface.

#### I2C Configuration
This code currently only demonstrates using the SPI interface.

