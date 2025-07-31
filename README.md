# Earthquake-Detection-

Overview
The system monitors ground motion and activates an audible alarm when significant vibrations are detected. A 16x2 LCD screen displays real-time status updates, informing users whether conditions are safe or if a tremor has been detected.

Objectives
Design a simple, cost-effective earthquake detection system.

Use an accelerometer (ADXL345) to detect seismic vibrations.

Provide immediate alerts using a buzzer and visual status through an LCD.

Serve as an educational tool for students learning about embedded systems.

Components Required
Arduino Uno

ADXL345 Accelerometer

16x2 LCD Display (without I2C)

Piezoelectric Buzzer

Resistors (220Ω)

Breadboard and Jumper Wires

9V Battery or USB Cable for Power

Working Principle
The ADXL345 sensor constantly measures acceleration in three axes. These values are read by the Arduino and compared against a predefined threshold. If the threshold is exceeded (indicating a tremor), the buzzer is activated and a warning message is shown on the LCD display. If no significant vibration is detected, the system continues to display a "Safe" status and keeps the buzzer off.

Features
Real-time vibration monitoring using ADXL345.

Immediate audible (buzzer) and visual (LCD) alerts.

Easy to build with low-cost components.

Power via USB or 9V battery for portability.

Modular for further development or integration with IoT.

Future Enhancements
Integrate with IoT modules (e.g., ESP8266) for remote monitoring.

Add GSM module to send SMS alerts during seismic activity.

Visualize vibration data on a dashboard using serial or network communication.

Applications
Educational projects in schools and colleges.

Fire drills and emergency training setups.

DIY safety solutions for small offices and homes.
