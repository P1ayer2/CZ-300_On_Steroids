### Big thanks to @jnorre for reverse-engineering all pins on this motherboard! 

## Pins
Rev.2 June 25 2023

[End stops]
x-stop: SIG-GND-3V3	SIG (IN) = pin 75 = PC17
y-stop: SIG-GND-3V3	SIG (IN) = pin 75 = PA0
z-stop: SIG-GND-3V3	SIG (IN) = pin 73 = PC16

[Fans]
FAN:	3V3-SIG		SIG (OUT) = pin 21 = PC13 
FAN2:   3V3-SIG		SIG (OUT) = pin 8 = PC31

[Heat]
BED:		(out) pin 22 = PA23
EXTRUDER:	(out) pin 24 = PA20

[Thermistors]
Bed:		(Ain) pin 3 = AD4 (PB0)  10k->Vcc, Inline 100ohm
Extruder:	(Ain) pin 4 = AD13 (PC29) 1k->Vcc, Inline 100ohm

[Steppers] A5984
X-Step:		(out) Pin 18 = PA19
X-Dir:		(out) Pin 17 = PC27
X-Enable:	(out) Pin 19 = PC15

Y-Step:		(out) Pin 52 = PA6
Y-Dir:		(out) pin 90 = PC23
Y-Enable:	(out) Pin 53 = PA5

Z-Step:		(out) Pin 14 = PA18
Z-Dir:		(out) Pin 13 = PC26
Z-Enable:	(out) Pin 12 = PA17

E-Step:		(out) Pin 67 = PA2
E-Dir:		(out) Pin 65 = PC10
E-Enable:	(out) Pin 68 = PC11

[SENSOR E1]
1: Pin 72 = PA1
2: Pin 71 = PC14
3: GND
4: 3V3

[LED]
1: Pin 99 = PB14/DAC1

[Calibration]
1: Pin 34 = PA24
2:          GND
3:          3V3

[DEBUG]
1: Pin 44 = PA10/PGMM1
2:          3V3
3:          GND
4: Pin 46 = PA9/PGMM2

[Display]
          3V3 -> DISP.1  -> HD44780.1  -> 3V3 display
          GND -> DISP.2  -> HD44780.2  -> GND
Pin 54 = PC28 -> DISP.3  -> HD44780.4  -> D/I
Pin 58 = PC8  -> DISP.4  -> HD44780.5  -> R/W
Pin 20 = PA22 -> DISP.5  -> HD44780.6  -> E
Pin 25 = PC0  -> DISP.6  -> HD44780.7  -> D0
Pin 47 = PC1  -> DISP.7  -> HD44780.8  -> D1
Pin 43 = PC2  -> DISP.8  -> HD44780.9  -> D2
Pin 40 = PC3  -> DISP.9  -> HD44780.10 -> D3
Pin 37 = PC4  -> DISP.10 -> HD44780.11 -> D4
Pin 35 = PC5  -> DISP.11 -> HD44780.12 -> D5
Pin 32 = PC6  -> DISP.12 -> HD44780.13 -> D6
Pin 29 = PC7  -> DISP.13 -> HD44780.14 -> D7
Pin 33 = PA13 -> DISP.14 -> HD44780.20 -> VSS (Backlight/Switched)
Pin 23 = PC12 -> DISP.15 -> Encoder.B
Pin 15 = PA21 -> DISP.16 -> Encoder.A
Pin 8  = PC31 -> DISP.17 -> Encoder.SWITCH  pin 9/PB3?
Pin 30 = PA15 -> DISP.18 -> HD44780.17 -> RESET
Pin 28 = PA16 -> DISP.19 -> Buzzer
Pin 51 = PB4  -> DISP.20 -> HD44780.15 -> CS1
Pin 87 = PB12 -> DISP.21 -> Reset.SWITCH
           NC -> DISP.22 -> NC

[SD-Card]
Pin 59 = PA28	-> SD.12 -> SD.Socket.2 = CMD
Pin 57 = PA27	-> SD.14 -> SD.Socket.1 = DAT3
Pin 39 = PA26	-> SD.16 -> SD.Socket.9 = DAT2
Pin 81 = PA31	-> SD.3  -> SD.Socket.8 = DAT1
Pin 64 = PA30	-> SD.5  -> SD.Socket.7 = DAT0
Pin 63 = PA29	-> SD.7  -> SD.Socket.6 = CLK
VDD    		-> SD.9  -> SD.Socket.4 = VDD (Power) Also SD.8
GND    		-> SD.2  -> SD.Socket.3 = VSS1 (GND), Also SD.4, SD.6, SD.10 and SD.11, SD.13, SD.15
GND    		-> *     -> SD.Socket.6 = VSS2 (GND) *: se above


[Burning]/[SWD]
1:          3V3
2: PIN 79 = TMS/SWDIO/PB6
3:          GND
4: PIN 76 = TDO/TRACESWO/PB5
5: PIN 83 = TCK/SWCLK/PB7
6: PIN 60 = NRST

Suggestion:
Part fan -> FAN2
3D touch: Home-Z + Calibration


