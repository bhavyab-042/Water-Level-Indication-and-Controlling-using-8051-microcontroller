# Water-Level-Indication-and-Controlling-using-8051-microcontroller
Water Level Controller using 8051 Microcontroller project will help in automatically controlling the water motor by sensing the water level in a tank. This system monitors the water level of the tank and automatically switches ON the motor whenever tank is empty. The motor is switched OFF when the overhead tank or container is FULL.

# Components Required :
* AT89C51 Microcontroller (or any 8051 based Microcontroller)
* 8051 Programmer (Programming Board)
* 11.0592 MHz Quartz Crystal
* 2 x 33pF Capacitor
* 2 x 10KΩ Resistor (1/4 Watt)
* 10µF Capacitor
* Push Button
* 1KΩ x 8 Resistor Pack (for Pull – up)
* 16 x 2 LCD Display
* 5V Relay
* 4 x 2N2222 (NPN) Transistors
* DC Motor (for demonstration)
* 10KΩ Potentiometer
* 1N4007 PN Junction Diode
* Programming cable
* Connecting wires
* Power Supply
* Keil µVision IDE
* Willar Software (for burning code)
* Proteus (for circuit diagram)

# Algorithm :
* First configure the controller pins P0.0, P0.1 and P0.2 as inputs and P0.7 as output.
* Now, initialize the LCD.
* Continuously check the water level input pins P0.0, P0.1 and P0.2.
* If all the pins are low, then display tank as “EMPTY” on the LCD and make P0.7 pin HIGH to run the motor automatically.
* If the level is low i.e. if P0.0 is HIGH, display the water level as “LOW” and continue to run the motor.  
* A HIGH pulse on the pin P0.1 indicates that water has reached half level. So, display the same thing on LCD and run the motor normally.
* If P0.2 is HIGH, then the water level in the tank is FULL.
* Now, make the P0.7 pin as LOW to turn off the motor automatically.


