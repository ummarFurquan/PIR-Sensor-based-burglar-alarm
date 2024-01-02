# PIR Sensor Burglar Alarm with Arduino Uno

This project implements a simple burglar alarm system using a Passive Infrared (PIR) sensor and an Arduino Uno. When motion is detected by the PIR sensor, the system activates an LED and a buzzer to alert of potential intrusion.

## Components

- Arduino Uno
- PIR Sensor
- LED
- Buzzer
- LDR (Light Dependent Resistor)
- Resistor
- Jumper Wires

## Wiring

- Connect the PIR sensor to the Arduino Uno:

  - VCC to 5V
  - GND to GND
  - OUT to Digital Pin 2

- Connect the LED to the Arduino Uno:

  - Anode (longer leg) to Digital Pin 6
  - Cathode (shorter leg) to GND through a current-limiting resistor

- Connect the Buzzer to the Arduino Uno:

  - Positive (usually red) to Digital Pin 6
  - Negative (usually black) to GND

- Connect the LDR to the Arduino Uno:

  - One leg to Analog Pin A0
  - The other leg to GND

Usage

   1. Connect the components as per the wiring instructions.
   2. Upload the provided Arduino code to the Arduino Uno using the Arduino IDE.
   3. Power up the Arduino Uno.
   4. Observe the LED and Buzzer behavior based on motion detected by the PIR sensor.

Customization

   1. Adjust sensitivity and delay parameters in the code.
   2. Add additional features or sensors for enhanced security.

Feel free to modify the code and circuit according to your specific requirements.
