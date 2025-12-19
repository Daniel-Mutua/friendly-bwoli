[README_Sequential_LED_Control.md](https://github.com/user-attachments/files/24263651/README_Sequential_LED_Control.md)
# Sequential LED Control – Arduino

## Description
This Arduino sketch demonstrates how to sequentially turn **three LEDs ON and OFF** using digital output pins and delays.  
Each LED is switched on and off with different time intervals to clearly show the sequence.

This program is suitable for **beginner Arduino learners** and is commonly used in **microcontroller and embedded systems practicals**.

---

## Hardware Requirements
- Arduino board (Uno, Mega, Nano, etc.)
- 3 LEDs
- 3 × 220Ω or 330Ω resistors
- Breadboard
- Jumper wires

---

## Pin Connections
| LED  | Arduino Pin |
|-----|-------------|
| LED1 | Pin 10 |
| LED2 | Pin 9 |
| LED3 | Pin 8 |

**Connection Guide:**
- Connect the **anode (long leg)** of each LED to the specified Arduino pin through a resistor.
- Connect the **cathode (short leg)** of each LED to **GND**.

---

## Software Requirements
- Arduino IDE (version 1.8.x or later)

---

## Program Explanation
1. Three variables are declared to represent LED pins (8, 9, and 10).
2. The `setup()` function sets all LED pins as OUTPUT.
3. The `loop()` function:
   - Turns ON LEDs one after another with increasing delays.
   - Turns OFF LEDs one after another with different delays.
   - Repeats the sequence continuously.

---

## Timing Sequence
| Action | Delay |
|------|-------|
| LED1 ON | 200 ms |
| LED2 ON | 400 ms |
| LED3 ON | 600 ms |
| LED1 OFF | 300 ms |
| LED2 OFF | 500 ms |
| LED3 OFF | 600 ms |

---

## How to Run the Program
1. Open the Arduino IDE.
2. Copy and paste the code into a new sketch.
3. Select the correct **Board** and **Port** from the Tools menu.
4. Click **Upload**.
5. Observe the LEDs lighting up sequentially.

---

## Learning Outcomes
- Understanding `pinMode()` and `digitalWrite()`
- Using delays for timing control
- Basic sequential logic in embedded systems

---

## License
This project is open for educational and academic use.
