# dc-chopper-python
Python-controlled DC chopper for motor speed control using Arduino, MOSFET, and PWM.


## 🎯 Project Overview
- Python sends PWM commands (0-100%) via USB
- Arduino converts to PWM signal
- MOSFET switches motor power
- Flyback diode protects MOSFET

## 🛠️ Components
- Arduino Uno
- IRF540 / IRFZ44N MOSFET
- 1N4007 Diode
- 220Ω Resistor
- DC Motor (6-12V)
- 12V Power Supply
- Breadboard + Jumper Wires

## 🔧 Circuit ConnectionArduino :
1, Pin 9 → 220Ω → MOSFET Gate

2, MOSFET Source → GND and 12- supply (-) connect together
 
3, MOSFET Drain → Motor (-)

4, Motor (+) → 12V Supply (+)

5, Diode ACROSS Motor (Band toward +)

## 📺 YouTube Tutorial
https://youtu.be/GmGzpH8uKuk



