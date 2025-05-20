# Vehicle-Blindspot-detection

An Arduino-based safety system designed to detect vehicles or obstacles in a driver's blind spot using Infrared (IR) sensors. This project enhances driving safety, particularly during lane changes, by providing real-time alerts when something enters the vehicle's blind zone.

---

## 🔧 How It Works

The system uses multiple IR proximity sensors mounted on the sides of the vehicle to detect objects in the blind spot area. When an object is detected within a preset range, a visual (LED) or audible (buzzer) alert is triggered to notify the driver.

---

## 🛠️ Components Used

| Component         | Quantity |
|------------------|----------|
| Arduino Uno/Nano | 1        |
| IR Sensors (TCRT5000 or similar) | 2-4      |
| LEDs             | 2-4      |
| Buzzer           | 1        |
| Resistors        | As needed|
| Breadboard/Wires | As needed|
| 12V Power Supply | 1        |

---

## 📦 Features

- 🔍 **IR-Based Obstacle Detection**
- ⚠️ **Visual & Audible Alerts**
- 🧠 **Arduino-Controlled Logic**
- 📏 **Adjustable Detection Range**
- 🔋 **Low Power Consumption**

---

## 🚀 Getting Started

### 1. Clone or Download the Code

### 2. Upload to Arduino
Open the .ino file in the Arduino IDE.

Connect your Arduino via USB.

Select the appropriate board and COM port.

Upload the code.

## Usage
Mount IR sensors on both sides of the vehicle (or prototype chassis).

Place alert LEDs or a buzzer within the driver's reach or field of view.

Power the system using a 12V battery or vehicle power supply.

The system continuously monitors side areas and alerts the driver if an object is detected.

## Code Logic Overview
cpp
Copy
Edit
if (irSensorLeft detects object || irSensorRight detects object) {
    trigger buzzer;
    turn on LED;
} else {
    turn off alerts;
}
## Future Improvements
✅ Replace IR sensors with Ultrasonic or Radar sensors for higher accuracy.

✅ Add display module for real-time object distance.

✅ Implement CAN Bus communication for integration with vehicle systems.

✅ Solar-powered version for energy efficiency.

## Applications
Educational electronics projects

Embedded systems or IoT coursework

Vehicle safety prototype for research

## Author
Saurav
GitHub: SauravD15
Email: saurabhdukare512@gmail.com

⭐ Support the Project
If you found this useful, give it a ⭐ on GitHub and share it with your peers!

yaml
Copy
Edit

Let me know if you'd like to include:

- A schematic in Fritzing or Proteus
- PCB design files
- A bill of materials (BOM) spreadsheet
- Simulation or testing results

I can help you format and attach those too.
