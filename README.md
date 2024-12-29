# CODTECH-TASK-2
Name: SUNNY GUPTA

Company: CODTECH IT SOLUTIONS

ID: CT08DMA

Domain: EMBEDDED SYSTEMS

Duration: 12TH DECEMBER 2024 TO 12 JANUARY 2025

Mentor: N.SANTHOSH


Project Name: Interface a DHT Sensor with Arduino and Display Readings on an LCD

Objective:
To measure temperature and humidity using a DHT sensor and display the readings on a 16x2 LCD screen using an Arduino.

Components Needed:
1.	Arduino Board (e.g., Arduino Uno, Nano, etc.)
2.	DHT Sensor (DHT11 or DHT22)
3.	16x2 LCD Display
4.	Resistor (10kΩ for DHT sensor pull-up)
5.	Breadboard
6.	Jumper Wires

Circuit Diagram:
DHT Sensor Connections:
1.	Connect the VCC pin of the DHT sensor to the 5V pin of the Arduino.
2.	Connect the GND pin to the GND pin of the Arduino.
3.	Connect the DATA pin to a digital pin on the Arduino (e.g., pin 2).
4.	Place a 10kΩ resistor between the DATA pin and VCC as a pull-up resistor.
16x2 LCD Connections:
1.	RS (Register Select): Connect to Arduino pin (e.g., pin 7).
2.	E (Enable): Connect to Arduino pin (e.g., pin 6).
3.	D4-D7 (Data Pins): Connect to Arduino pins (e.g., pins 5, 4, 3, 2 respectively).
4.	VSS and RW: Connect both to the GND pin of Arduino.
5.	VCC: Connect to the 5V pin of Arduino.
6.	Backlight Pins (A and K): Connect A to 5V and K to GND.

Steps:
1.	Connect the Components:
o	Assemble the DHT sensor and 16x2 LCD as per the circuit diagram.
o	Ensure proper connections for the DHT sensor with the pull-up resistor.
2.	Set the Contrast of LCD:
o	Instead of using a potentiometer, use a fixed resistor (e.g., 1kΩ) between the V0 (contrast pin) of the LCD and GND.
3.	Power the Circuit:
o	Connect the Arduino to your computer or a 5V power supply.
o	Verify that the LCD powers up and initializes.
4.	Test the Sensor and LCD:
o	Check the wiring to ensure all connections are secure.
o	Verify that the DHT sensor readings are displayed correctly on the LCD.

Key Activities:
1.	Designing and assembling the circuit on a breadboard.
2.	Connecting the DHT sensor and LCD to the Arduino.
3.	Adjusting the LCD contrast using a fixed resistor.
4.	Testing and troubleshooting to ensure proper display of temperature and humidity readings.


OUTPUT ATTACHED.
