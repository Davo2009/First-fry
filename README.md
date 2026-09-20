# Arduino 4-Bit Binary Counter

## 📌 Overview
Briefly describe what this project does. For example: *A 4-bit binary counter implemented on an Arduino Uno using C++. The system sequences through binary values from 0 (0000) to 15 (1111) using an array of 4 LEDs.*

---

## 🛠️ Components & Tools
* **Hardware:** Arduino Uno, 4x LEDs, 4x 1kΩ resistors, Solderless Breadboard, Jumper wires
* **Software Environment:** Tinkercad Circuits / Arduino IDE / Visual Studio
* **Language:** C++

---

## 🔌 Circuit Wiring & Schematic
* **Pin 8 (Bit 0):** Connected to Red LED anode via a 1kΩ series resistor.
* **Pin 9 (Bit 1):** Connected to Blue LED anode via a 1kΩ series resistor.
* **Pin 11 (Bit 2):** Connected to Green LED anode via a 1kΩ series resistor.
* **Pin 12 (Bit 3):** Connected to Yellow LED anode via a 1kΩ series resistor.
* **Ground (GND):** Common negative rail return path connected to all LED cathodes.

--
Challenges & Troubleshooting
Issue: (e.g., Overcurrent warning symbol on LED during simulation).

Root Cause: (e.g., Bypassing the series current-limiting resistor by wiring directly into the anode column).

Solution: (e.g., Rerouted the pin input directly into the resistor terminal to drop voltage safely).

🚀 Key Takeaways
Learned how digital output registers (pinMode, digitalWrite) control hardware states.

Practiced safe breadboard prototyping and circuit debugging.
