# Earthquake Detection and Alert System using Arduino Uno

A low-cost prototype that detects ground vibrations and triggers real-time alerts using an Arduino Uno and ADXL345 accelerometer. This project is intended for educational purposes and aims to raise awareness about seismic safety.

---

## 🔍 Overview

This system uses the ADXL345 accelerometer to detect sudden vibrations. Upon detecting a tremor, it activates a piezo buzzer and updates a 16x2 LCD display with real-time status messages.

---

## 🎯 Objectives

- Develop a simple and affordable earthquake detection prototype.
- Use an accelerometer to sense real-time seismic activity.
- Trigger immediate audible and visual alerts upon detection.
- Serve as an educational project for electronics and embedded systems.

---

## 🛠 Components Required

| Component              | Quantity |
|------------------------|----------|
| Arduino Uno            | 1        |
| ADXL345 Accelerometer  | 1        |
| 16x2 LCD Display       | 1        |
| Piezo Buzzer           | 1        |
| Resistors (220Ω)       | Few      |
| Breadboard + Jumpers   | As needed|
| 9V Battery / USB Cable | 1        |

---

## ⚙️ Working Principle

- The ADXL345 continuously monitors acceleration in X, Y, and Z axes.
- When the readings exceed a predefined threshold, a tremor is assumed.
- A piezo buzzer alerts the user, and the LCD displays a warning.
- If below the threshold, the LCD shows "Safe" and buzzer remains off.

---

## ✨ Features

- Real-time ground vibration detection.
- Audible buzzer alert for high vibration levels.
- LCD display for current seismic status.
- Powered by USB or 9V battery.
- Affordable and beginner-friendly hardware.

---

## 🚀 Future Enhancements

- Add IoT capability (e.g., ESP8266) for remote alerting.
- Integrate GSM module to send SMS during earthquakes.
- Log and graph acceleration data over time.

---

## 📦 Applications

- Educational STEM kits and workshops.
- Earthquake preparedness demonstrations.
- DIY home safety alerts.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use it for educational purposes.

---

## 💡 Author

[Yash Raj](https://github.com/dark1612)
