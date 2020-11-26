EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date "15 nov 2012"
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L power:+5V #PWR01
U 1 1 580C1B61
P 3100 950
F 0 "#PWR01" H 3100 800 50  0001 C CNN
F 1 "+5V" H 3100 1090 50  0000 C CNN
F 2 "" H 3100 950 50  0000 C CNN
F 3 "" H 3100 950 50  0000 C CNN
	1    3100 950 
	1    0    0    -1  
$EndComp
Wire Wire Line
	3100 950  3100 1100
Wire Wire Line
	3100 1100 2900 1100
Wire Wire Line
	3100 1200 2900 1200
Connection ~ 3100 1100
$Comp
L power:GND #PWR02
U 1 1 580C1D11
P 3000 3150
F 0 "#PWR02" H 3000 2900 50  0001 C CNN
F 1 "GND" H 3000 3000 50  0000 C CNN
F 2 "" H 3000 3150 50  0000 C CNN
F 3 "" H 3000 3150 50  0000 C CNN
	1    3000 3150
	1    0    0    -1  
$EndComp
Wire Wire Line
	3000 1300 3000 1700
Wire Wire Line
	3000 2700 2900 2700
Wire Wire Line
	3000 2500 2900 2500
Connection ~ 3000 2700
Wire Wire Line
	3000 2000 2900 2000
Connection ~ 3000 2500
Wire Wire Line
	3000 1700 2900 1700
Connection ~ 3000 2000
$Comp
L power:GND #PWR03
U 1 1 580C1E01
P 2300 3150
F 0 "#PWR03" H 2300 2900 50  0001 C CNN
F 1 "GND" H 2300 3000 50  0000 C CNN
F 2 "" H 2300 3150 50  0000 C CNN
F 3 "" H 2300 3150 50  0000 C CNN
	1    2300 3150
	1    0    0    -1  
$EndComp
Wire Wire Line
	2300 3000 2400 3000
Wire Wire Line
	2300 1500 2300 2300
Wire Wire Line
	2300 2300 2400 2300
Connection ~ 2300 3000
Connection ~ 2200 1100
Wire Wire Line
	2200 1900 2400 1900
Wire Wire Line
	2200 1100 2400 1100
Wire Wire Line
	2200 950  2200 1100
$Comp
L power:+3.3V #PWR04
U 1 1 580C1BC1
P 2200 950
F 0 "#PWR04" H 2200 800 50  0001 C CNN
F 1 "+3.3V" H 2200 1090 50  0000 C CNN
F 2 "" H 2200 950 50  0000 C CNN
F 3 "" H 2200 950 50  0000 C CNN
	1    2200 950 
	1    0    0    -1  
$EndComp
Wire Wire Line
	2300 1500 2400 1500
Connection ~ 2300 2300
Wire Wire Line
	2400 1200 1250 1200
Wire Wire Line
	1250 1300 2400 1300
Wire Wire Line
	1250 1400 2400 1400
Wire Wire Line
	2400 1600 1250 1600
Wire Wire Line
	1250 1700 2400 1700
Wire Wire Line
	1250 1800 2400 1800
Wire Wire Line
	1250 2200 2400 2200
Wire Wire Line
	1250 2600 2400 2600
Wire Wire Line
	2900 2900 3950 2900
Wire Wire Line
	2900 2200 3950 2200
Wire Wire Line
	2900 1800 3950 1800
Wire Wire Line
	2900 1900 3950 1900
Wire Wire Line
	2900 1500 3950 1500
Wire Wire Line
	2900 1600 3950 1600
Wire Wire Line
	2900 1400 3950 1400
Text Label 1250 1200 0    50   ~ 0
GPIO2(SDA1)
Text Label 1250 1300 0    50   ~ 0
GPIO3(SCL1)
Text Label 1250 1400 0    50   ~ 0
GPIO4(GCLK)
Text Label 1250 1600 0    50   ~ 0
GPIO17(GEN0)
Text Label 1250 1700 0    50   ~ 0
GPIO27(GEN2)
Text Label 1250 1800 0    50   ~ 0
GPIO22(GEN3)
Text Label 1250 2000 0    50   ~ 0
DIN
Text Label 1250 2100 0    50   ~ 0
DOUT
Text Label 1250 2200 0    50   ~ 0
SCK
Text Label 1250 2400 0    50   ~ 0
ID_SD
Text Label 1250 2500 0    50   ~ 0
GPIO5
Text Label 1250 2600 0    50   ~ 0
GPIO6
Text Label 1250 2700 0    50   ~ 0
EOC
Text Label 1250 2800 0    50   ~ 0
GPIO19(SPI1_MISO)
Text Label 1250 2900 0    50   ~ 0
GPIO26
Text Label 3950 2900 2    50   ~ 0
GPIO20(SPI1_MOSI)
Text Label 3950 2800 2    50   ~ 0
GPIO16
Text Label 3950 2600 2    50   ~ 0
GPIO12(PWM0)
Text Label 3950 2400 2    50   ~ 0
ID_SC
Text Label 3950 2300 2    50   ~ 0
GPIO7(SPI1_CE_N)
Text Label 3950 2200 2    50   ~ 0
CS
Text Label 3950 2100 2    50   ~ 0
GPIO25(GEN6)
Text Label 3950 1900 2    50   ~ 0
GPIO24(GEN5)
Text Label 3950 1800 2    50   ~ 0
GPIO23(GEN4)
Text Label 3950 1600 2    50   ~ 0
GPIO18(GEN1)(PWM0)
Text Label 3950 1500 2    50   ~ 0
GPIO15(RXD0)
Text Label 3950 1400 2    50   ~ 0
GPIO14(TXD0)
Wire Wire Line
	3000 1300 2900 1300
Connection ~ 3000 1700
Text Notes 650  7600 0    50   ~ 0
ID_SD and ID_SC PINS:\nThese pins are reserved for HAT ID EEPROM.\n\nAt boot time this I2C interface will be\ninterrogated to look for an EEPROM\nthat identifes the attached board and\nallows automagic setup of the GPIOs\n(and optionally, Linux drivers).\n\nDO NOT USE these pins for anything other\nthan attaching an I2C ID EEPROM. Leave\nunconnected if ID EEPROM not required.
$Comp
L pcb_pi_max11642eeg-rescue:Mounting_Hole-Mechanical MK1
U 1 1 5834FB2E
P 3000 7200
F 0 "MK1" H 3100 7246 50  0000 L CNN
F 1 "M2.5" H 3100 7155 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.7mm_M2.5" H 3000 7200 60  0001 C CNN
F 3 "" H 3000 7200 60  0001 C CNN
	1    3000 7200
	1    0    0    -1  
$EndComp
$Comp
L pcb_pi_max11642eeg-rescue:Mounting_Hole-Mechanical MK3
U 1 1 5834FBEF
P 3450 7200
F 0 "MK3" H 3550 7246 50  0000 L CNN
F 1 "M2.5" H 3550 7155 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.7mm_M2.5" H 3450 7200 60  0001 C CNN
F 3 "" H 3450 7200 60  0001 C CNN
	1    3450 7200
	1    0    0    -1  
$EndComp
$Comp
L pcb_pi_max11642eeg-rescue:Mounting_Hole-Mechanical MK2
U 1 1 5834FC19
P 3000 7400
F 0 "MK2" H 3100 7446 50  0000 L CNN
F 1 "M2.5" H 3100 7355 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.7mm_M2.5" H 3000 7400 60  0001 C CNN
F 3 "" H 3000 7400 60  0001 C CNN
	1    3000 7400
	1    0    0    -1  
$EndComp
$Comp
L pcb_pi_max11642eeg-rescue:Mounting_Hole-Mechanical MK4
U 1 1 5834FC4F
P 3450 7400
F 0 "MK4" H 3550 7446 50  0000 L CNN
F 1 "M2.5" H 3550 7355 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.7mm_M2.5" H 3450 7400 60  0001 C CNN
F 3 "" H 3450 7400 60  0001 C CNN
	1    3450 7400
	1    0    0    -1  
$EndComp
Text Notes 3000 7050 0    50   ~ 0
Mounting Holes
$Comp
L Connector_Generic:Conn_02x20_Odd_Even P1
U 1 1 59AD464A
P 2600 2000
F 0 "P1" H 2650 3117 50  0000 C CNN
F 1 "Conn_02x20_Odd_Even" H 2650 3026 50  0000 C CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_2x20_P2.54mm_Vertical" H -2250 1050 50  0001 C CNN
F 3 "" H -2250 1050 50  0001 C CNN
	1    2600 2000
	1    0    0    -1  
$EndComp
Text Label 3950 3000 2    50   ~ 0
GPIO21(SPI1_SCK)
Wire Wire Line
	3100 1100 3100 1200
Wire Wire Line
	3000 2700 3000 3150
Wire Wire Line
	3000 2500 3000 2700
Wire Wire Line
	3000 2000 3000 2500
Wire Wire Line
	2300 3000 2300 3150
Wire Wire Line
	2200 1100 2200 1900
Wire Wire Line
	2300 2300 2300 3000
Wire Wire Line
	3000 1700 3000 2000
Wire Wire Line
	7250 5850 6800 5850
$Comp
L power:GND #PWR0101
U 1 1 5F50043B
P 6800 5950
F 0 "#PWR0101" H 6800 5700 50  0001 C CNN
F 1 "GND" H 6805 5777 50  0000 C CNN
F 2 "" H 6800 5950 50  0001 C CNN
F 3 "" H 6800 5950 50  0001 C CNN
	1    6800 5950
	1    0    0    -1  
$EndComp
Wire Wire Line
	7250 5950 6800 5950
Text Label 5150 5950 0    50   ~ 0
AIN15
Wire Wire Line
	5150 5950 5600 5950
Wire Wire Line
	5150 5850 5600 5850
Wire Wire Line
	5150 5750 5600 5750
Wire Wire Line
	5150 5650 5600 5650
Wire Wire Line
	5150 5550 5600 5550
Wire Wire Line
	5150 5450 5600 5450
Wire Wire Line
	5150 5350 5600 5350
Wire Wire Line
	3500 5950 3950 5950
Wire Wire Line
	3500 5850 3950 5850
Wire Wire Line
	5150 5250 5600 5250
Wire Wire Line
	3500 5750 3950 5750
Wire Wire Line
	3500 5650 3950 5650
Wire Wire Line
	3500 5550 3950 5550
Wire Wire Line
	3500 5450 3950 5450
Wire Wire Line
	3500 5350 3950 5350
Wire Wire Line
	3500 5250 3950 5250
Text Label 3500 5250 0    50   ~ 0
AIN0
Text Label 3500 5350 0    50   ~ 0
AIN1
Text Label 3500 5450 0    50   ~ 0
AIN2
Text Label 3500 5550 0    50   ~ 0
AIN3
Text Label 3500 5650 0    50   ~ 0
AIN4
Text Label 3500 5750 0    50   ~ 0
AIN5
Text Label 3500 5850 0    50   ~ 0
AIN6
Text Label 3500 5950 0    50   ~ 0
AIN7
Text Label 5150 5250 0    50   ~ 0
AIN8
Text Label 5150 5350 0    50   ~ 0
AIN9
Text Label 5150 5450 0    50   ~ 0
AIN10
Text Label 5150 5550 0    50   ~ 0
AIN11
Text Label 5150 5650 0    50   ~ 0
AIN12
Text Label 5150 5750 0    50   ~ 0
AIN13
Text Label 5150 5850 0    50   ~ 0
AIN14
Text Label 7150 1950 0    50   ~ 0
AIN15
Wire Wire Line
	7150 1950 7600 1950
Text Label 7150 2050 0    50   ~ 0
AIN0
Text Notes 7800 1250 0    118  ~ 24
16 Channel ADC\n[MAX11642EEG]
$Comp
L power:GND #PWR0102
U 1 1 5F56383C
P 9850 4350
F 0 "#PWR0102" H 9850 4100 50  0001 C CNN
F 1 "GND" H 9855 4177 50  0000 C CNN
F 2 "" H 9850 4350 50  0001 C CNN
F 3 "" H 9850 4350 50  0001 C CNN
	1    9850 4350
	1    0    0    -1  
$EndComp
Text Label 9700 1750 0    50   ~ 0
P5V_HAT
Text Label 9700 1950 0    50   ~ 0
DOUT
Wire Wire Line
	9850 1950 9400 1950
Wire Wire Line
	9850 4350 9400 4350
$Comp
L MAX11642EEG:MAX11642EEG U1
U 1 1 5F4C90DF
P 8500 3050
F 0 "U1" H 8500 4620 50  0000 C CNN
F 1 "MAX11642EEG" H 8500 4529 50  0000 C CNN
F 2 "Package_SO:QSOP-24_3.9x8.7mm_P0.635mm" H 8500 3050 50  0001 L BNN
F 3 "" H 8500 3050 50  0001 C CNN
	1    8500 3050
	1    0    0    -1  
$EndComp
Wire Wire Line
	9850 1750 9550 1750
Wire Wire Line
	7150 3950 7600 3950
Wire Wire Line
	7150 3750 7600 3750
Wire Wire Line
	7150 3550 7600 3550
Wire Wire Line
	7150 3450 7600 3450
Wire Wire Line
	7150 3350 7600 3350
Wire Wire Line
	7150 3250 7600 3250
Wire Wire Line
	7150 3150 7600 3150
Wire Wire Line
	7150 3050 7600 3050
Wire Wire Line
	7150 2950 7600 2950
Wire Wire Line
	7150 2750 7600 2750
Wire Wire Line
	7150 2650 7600 2650
Wire Wire Line
	7150 2850 7600 2850
Wire Wire Line
	7150 2550 7600 2550
Wire Wire Line
	7150 2450 7600 2450
Wire Wire Line
	7150 2350 7600 2350
Wire Wire Line
	7150 2250 7600 2250
Wire Wire Line
	7150 2150 7600 2150
Wire Wire Line
	7150 2050 7600 2050
Text Label 7150 2150 0    50   ~ 0
AIN1
Text Label 7150 2250 0    50   ~ 0
AIN2
Text Label 7150 2350 0    50   ~ 0
AIN3
Text Label 7150 2450 0    50   ~ 0
AIN4
Text Label 7150 2550 0    50   ~ 0
AIN5
Text Label 7150 2650 0    50   ~ 0
AIN6
Text Label 7150 2750 0    50   ~ 0
AIN7
Text Label 7150 2850 0    50   ~ 0
AIN8
Text Label 7150 2950 0    50   ~ 0
AIN9
Text Label 7150 3050 0    50   ~ 0
AIN10
Text Label 7150 3150 0    50   ~ 0
AIN11
Text Label 7150 3250 0    50   ~ 0
AIN12
Text Label 7150 3350 0    50   ~ 0
AIN13
Text Label 7150 3450 0    50   ~ 0
AIN14
Text Label 7150 3550 0    50   ~ 0
DIN
Text Label 7150 3750 0    50   ~ 0
SCK
Wire Wire Line
	6800 5850 6800 5950
Connection ~ 6800 5950
Text Notes 3300 5050 0    118  ~ 24
8 Pin Screw Terminals [AIN array/GND/3.3V out]
Text Label 9600 4350 0    50   ~ 0
GND
Text Label 6950 5850 0    50   ~ 0
GND
Text Label 6950 5950 0    50   ~ 0
GND
$Comp
L Device:C C1
U 1 1 5F4F9DFB
P 9550 1600
F 0 "C1" H 9665 1646 50  0000 L CNN
F 1 "0.1uF" H 9665 1555 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D4.0mm_P2.00mm" H 9588 1450 50  0001 C CNN
F 3 "~" H 9550 1600 50  0001 C CNN
	1    9550 1600
	1    0    0    -1  
$EndComp
Connection ~ 9550 1750
Wire Wire Line
	9550 1750 9400 1750
Wire Wire Line
	9550 1450 9550 1350
Wire Wire Line
	9550 1350 10000 1350
Wire Wire Line
	10000 1350 10000 1400
$Comp
L power:GND #PWR0103
U 1 1 5F4FD94F
P 10000 1400
F 0 "#PWR0103" H 10000 1150 50  0001 C CNN
F 1 "GND" H 10005 1227 50  0000 C CNN
F 2 "" H 10000 1400 50  0001 C CNN
F 3 "" H 10000 1400 50  0001 C CNN
	1    10000 1400
	1    0    0    -1  
$EndComp
Text Label 9850 1350 0    50   ~ 0
GND
Wire Wire Line
	7600 3650 6800 3650
$Comp
L Device:C C2
U 1 1 5F503505
P 6800 3800
F 0 "C2" H 6915 3846 50  0000 L CNN
F 1 "0.1uF" H 6915 3755 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D4.0mm_P2.00mm" H 6838 3650 50  0001 C CNN
F 3 "~" H 6800 3800 50  0001 C CNN
	1    6800 3800
	1    0    0    -1  
$EndComp
Wire Wire Line
	6800 3950 6800 4150
$Comp
L power:GND #PWR0104
U 1 1 5F50AF0A
P 6800 4150
F 0 "#PWR0104" H 6800 3900 50  0001 C CNN
F 1 "GND" H 6805 3977 50  0000 C CNN
F 2 "" H 6800 4150 50  0001 C CNN
F 3 "" H 6800 4150 50  0001 C CNN
	1    6800 4150
	1    0    0    -1  
$EndComp
Text Label 6800 4050 0    50   ~ 0
GND
Wire Wire Line
	7600 4150 7150 4150
Text Label 7150 4150 0    50   ~ 0
EOC
Connection ~ 6800 5850
Wire Wire Line
	7250 5650 6800 5650
Wire Wire Line
	6800 5650 6800 5750
Wire Wire Line
	7250 5750 6800 5750
Connection ~ 6800 5750
Wire Wire Line
	6800 5750 6800 5850
$Comp
L Connector:Screw_Terminal_01x08 J1
U 1 1 5F64396C
P 4150 5550
F 0 "J1" H 4230 5542 50  0000 L CNN
F 1 "Screw_Terminal_01x08" H 4230 5451 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-8_1x08_P5.00mm_Horizontal" H 4150 5550 50  0001 C CNN
F 3 "~" H 4150 5550 50  0001 C CNN
	1    4150 5550
	1    0    0    -1  
$EndComp
$Comp
L Connector:Screw_Terminal_01x08 J2
U 1 1 5F645FB7
P 5800 5550
F 0 "J2" H 5880 5542 50  0000 L CNN
F 1 "Screw_Terminal_01x08" H 5880 5451 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-8_1x08_P5.00mm_Horizontal" H 5800 5550 50  0001 C CNN
F 3 "~" H 5800 5550 50  0001 C CNN
	1    5800 5550
	1    0    0    -1  
$EndComp
$Comp
L Connector:Screw_Terminal_01x08 J3
U 1 1 5F649DC9
P 7450 5550
F 0 "J3" H 7530 5542 50  0000 L CNN
F 1 "Screw_Terminal_01x08" H 7530 5451 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-8_1x08_P5.00mm_Horizontal" H 7450 5550 50  0001 C CNN
F 3 "~" H 7450 5550 50  0001 C CNN
	1    7450 5550
	1    0    0    -1  
$EndComp
Wire Wire Line
	6800 5250 7250 5250
Text Label 6800 5250 0    50   ~ 0
P5V_HAT
Wire Wire Line
	6800 5350 7250 5350
Text Label 6800 5350 0    50   ~ 0
P5V_HAT
Wire Wire Line
	6800 5450 7250 5450
Text Label 6800 5450 0    50   ~ 0
P5V_HAT
Wire Wire Line
	6800 5550 7250 5550
Text Label 6800 5550 0    50   ~ 0
P5V_HAT
Text Label 6950 5750 0    50   ~ 0
GND
Text Label 6950 5650 0    50   ~ 0
GND
Text Notes 1850 750  0    118  ~ 24
Pi Header [40-pin]
Wire Wire Line
	2900 3000 3950 3000
Wire Wire Line
	2900 2800 3950 2800
Wire Wire Line
	2900 2600 3950 2600
Wire Wire Line
	2900 2400 3950 2400
Wire Wire Line
	2900 2300 3950 2300
Wire Wire Line
	2900 2100 3950 2100
Wire Wire Line
	1250 2900 2400 2900
Wire Wire Line
	1250 2800 2400 2800
Wire Wire Line
	2400 2700 1250 2700
Wire Wire Line
	1250 2500 2400 2500
Wire Wire Line
	2400 2400 1250 2400
Wire Wire Line
	1250 2100 2400 2100
Wire Wire Line
	2400 2000 1250 2000
Text Label 7150 3950 0    50   ~ 0
CS
Text Label 3400 1100 0    50   ~ 0
P5V_HAT
Wire Wire Line
	3100 1100 3550 1100
$EndSCHEMATC
