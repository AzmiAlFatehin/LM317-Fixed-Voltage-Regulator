LM317 Fixed Voltage Regulator

Project Overview

This project demonstrates a simple DC voltage regulator using the LM317 voltage regulator IC. The circuit is designed to provide a stable output voltage using fixed resistor values and filtering capacitors.

The regulator helps maintain a constant output voltage despite variations in input voltage and load conditions.

Components Used

- LM317 Voltage Regulator IC
- 240 Ω Resistor
- 1 kΩ Resistor
- 470 µF Capacitor × 2
- DC Power Supply
- Breadboard and Connecting Wires



Working Principle

The LM317 is a three-terminal adjustable voltage regulator. In this project, a 240 Ω resistor and a 1 kΩ resistor are used to set the output voltage.

The input capacitor helps reduce voltage fluctuations from the power source, while the output capacitor improves stability and reduces output noise.

Output Voltage

The output voltage:


 1. Test with 9V Battery Input

When a 9V DC battery was used as the input source, the measured output voltage was:

Input Voltage (Vin): 9.0 V (nominal)
Output Voltage (Vout): 3.69 V

This significant drop occurs due to:

Internal resistance of the battery
Voltage sag under load condition
Minimum dropout voltage requirement of LM317 (~2–3V)


2. Test with Variable DC Power Supply

When a regulated DC power supply was used:

Input Voltage (Vin): 18.75 V
Output Voltage (Vout): 8.68 V

The circuit maintained a more stable output because the supply had:

Lower internal resistance
Stable voltage under load


Applications

- Electronics Laboratory Experiments
- Educational Demonstrations
- Low-Power DC Supply Circuits
- Prototype Testing
- General Electronics Projects

Results

The circuit successfully regulated the input voltage and provided a stable DC output suitable for powering low-power electronic devices.

Future Improvements

- Add adjustable voltage control using a potentiometer
- Design a PCB version of the circuit
- Add current limiting and protection features
- Integrate a digital voltmeter display

Author

Azmi Al Fatehin

B.Sc. in Electrical and Electronic Engineering

Chair, IEEE Prime University Student Branch