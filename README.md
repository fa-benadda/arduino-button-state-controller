# Arduino Sequential State Controller 🚦

A simple yet effective Arduino embedded project that cycle-controls three LEDs (Green, Yellow, Red) sequentially using a single push button input.

---

## 📌 Features

* Multi-State Switching: Cycles through 3 distinct hardware states using counter increments.
* Debounce Protection: Includes a soft software delay to ensure clean input reads from the push button.
* Internal Pull-Up Resistance: Utilizes Arduino's internal INPUT_PULLUP resistor for a simplified circuit wiring.

---

## 🛠️ Hardware Requirements

* Arduino Uno (or compatible board)
* 1x Push Button
* 3x LEDs (Red, Yellow, Green)
* 3x 220Ω Resistors
* Breadboard & Jumper Wires

---

## 🔌 Circuit & Pinout Setup

| Component | Pin Connection | Note |
| :--- | :--- | :--- |
| Push Button | Digital Pin 2 | Connected using INPUT_PULLUP (GND logic) |
| Green LED | Digital Pin 3 | Connected via 220Ω resistor to GND |
| Yellow LED | Digital Pin 5 | Connected via 220Ω resistor to GND |
| Red LED | Digital Pin 6 | Connected via 220Ω resistor to GND |

---

## ⚙️ Logic Breakdown

1. **State 1 (x = 1):** Green LED ON, others OFF.
2. **State 2 (x = 2):** Yellow LED ON, others OFF.
3. **State 3 (x = 3):** Red LED ON, others OFF.

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open the .ino file in **ATinkercador **Tinkercad**.
3. Connect the hardware according to the pinout table.
4. Select your board and pUploadclick **Upload**.
