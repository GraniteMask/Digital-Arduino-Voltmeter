# Digital-Arduino-Voltmeter

An Arduino based Digital Voltmeter is designed in this project which can be used to measure different ranges of DC voltages. Arduino UNO microcontroller based digital voltmeter has been designed and developed with liquid crystal display and voltage range indicator.

![Sociogram Home Page](https://github.com/GraniteMask/Digital-Arduino-Voltmeter/blob/main/digital_arduino_voltmeter.png?raw=true)

## Abstract:

Analog Voltmeters generally have an error percentage of 5% and the parallax error is often an issue. But analog voltmeters can be used to measure ranging from few volts to several thousand volts.
To overcome the defects of analog voltmeters, Digital Voltmeters are introduced. Unlike analog voltmeters, which scale and a pointer to show the measured voltage, digital voltmeters directly display the measured voltage numerical on a digital display.
Also Digital Voltmeter is a voltage sensitive device which senses DC voltage and display it directly in numeric form instead of pointer deflection

## Components:

1) Arduino UNO
2) 16x2 LCD display
3) 10KΩ resistor ( 1 nos )
4) 220 Ω resistor ( 1 nos )
5) 1 M Ω resistor ( 1 nos )
6) Connecting wires
7) Battery
8) Breadboard

## Working:

In Digital Voltmeter,  Analog signals are provided that is the input voltage which is converted with the help of Analog to Digital converter. This converter is already there in Arduino UNO
The input voltage is given to Analog input pin i.e. A0 of the Arduino. The reference voltage for Analog to Digital converter is 5V.
Here a reference voltage of 5V has been developed to power up the Arduino
For Arduino the input voltage is calculated by multiplying the analog value with 5 and dividing it further by 1024.
With the help of the voltage divider circuit already present in the arduino, the input voltage being calculated is taken down to the range of Arduino UNOs analog input
The further specifications are made with the help of Arduino Code.
Then the calculated value of input voltage is displayed through LCD with some approximate value.

## Simulation Diagram ( by using TinkerCAD ):

![Sociogram Home Page](https://github.com/GraniteMask/Digital-Arduino-Voltmeter/blob/main/simulation.png?raw=true)

## Applications:

An Arduino based Digital Voltmeter is designed in this project which can be used to measure different ranges of DC voltages.
The circuit can be extended to measure even AC voltages with slight modification in circuit and code.

## My Fellow Team-mates:

HIMANSHU PATEL 
ISHIT MATHUR 
ASHUTOSH DWIVEDI 
