# Arduino 4-Digit 7-Segment Clock with 30/60 Minute Alarms

This project is a **digital clock** using a 4-digit 7-segment display controlled by an Arduino.  
The clock shows **minutes and seconds** and plays a **buzzer alarm** at 30 minutes and 60 minutes.

---

🎮 **How It Works**  
- Multiplexing is used to control all 4 digits efficiently.  
- The **minutes and seconds** are calculated from the Arduino `millis()` function.  
- The **buzzer** sounds three short beeps at 30 minutes and 60 minutes.  
- A startup tone plays when the Arduino powers on.  

---

✨ **What I Learned**  
Through this project, I practiced:  
- Controlling **4-digit 7-segment displays** with Arduino  
- Using **multiplexing** for efficient display  
- Implementing **time tracking** using `millis()`  
- Playing **alarms with a piezo buzzer**  

---

🛠️ **Components**  
- 1 × Arduino Uno (or compatible)  
- 1 × 4-Digit 7-Segment Display  
- 1 × Piezo buzzer  
- Jumper wires  
- Breadboard  

---

🔌 **Pin Connections**

| Segment | Arduino Pin | Digit | Arduino Pin |
|---------|-------------|-------|-------------|
| A       | 11          | 1     | 12          |
| B       | 7           | 2     | 9           |
| C       | 4           | 3     | 8           |
| D       | 2           | 4     | 6           |
| E       | 1           |       |             |
| F       | 10          |       |             |
| G       | 5           |       |             |
| DP      | 3           |       |             |
| Buzzer  | 13          |       |             |

---

▶️ **How to Run**  
1. Connect the 4-digit 7-segment display and buzzer according to the table above.  
2. Upload the `7SegmentClock.ino` sketch to your Arduino Uno.  
3. Power the Arduino.  
4. Watch the clock count minutes and seconds.  
5. Listen for the buzzer alarms at 30 and 60 minutes.  

---

💡 **Tip:**  
You can expand this project by adding **hours**, or linking it to a **DHT11 sensor** to combine a clock with temperature/humidity display.
