# ESP8266 Microwave Motion Sensor RADAR Sensor Project

#### Project Overview
This project demonstrates how to use an ESP8266 microcontroller with a microwave motion sensor RADAR module to detect motion in its surroundings. The RADAR sensor emits microwave signals and detects any reflected signals from moving objects, allowing the ESP8266 to monitor and report motion detection status through the Serial Monitor.

#### Components Needed
- **ESP8266 Microcontroller**
- **Microwave Motion Sensor RADAR Module**
- **Jumper Wires**

#### Block diagram


#### Circuit Setup
1. **Connecting the RADAR Sensor Module to ESP8266:**
   - Connect the digital output pin of the RADAR sensor module to GPIO pin D2 on the ESP8266.
   - Ensure proper power (VCC) and ground (GND) connections between the ESP8266 and the RADAR sensor module.

#### Instructions
1. **Setup:**
   - Open the Arduino IDE with ESP8266 board support installed.
   - Create a new sketch and paste the provided Arduino code.
   - Connect the ESP8266 to your computer, select the appropriate board and port from the Tools menu.
   - Upload the code to the ESP8266.

2. **Operation:**
   - After uploading the code, open the Serial Monitor (baud rate: 9600).
   - The Serial Monitor will display "Motion detected!" when motion is detected by the RADAR sensor module.
   - It will display "No motion detected" when no motion is detected.

#### Applications
- **Security Systems:** Use in alarms and monitoring systems for detecting intrusions.
- **Automation:** Trigger actions based on motion detection, such as turning on lights.
- **Occupancy Sensing:** Monitor room occupancy for energy efficiency in buildings.

#### Notes
- **Sensor Sensitivity:** Adjust the sensitivity of the RADAR sensor module for different detection ranges.
- **Digital Output:** The RADAR sensor module provides a digital signal (`LOW` or `HIGH`) based on motion detection.
- **Delay:** Adjust the delay between readings according to the desired responsiveness of the motion detection system.

---

#### Useful Links
🌐 [ProjectsLearner - ESP8266 Microwave Motion Sensor RADAR Sensor](https://projectslearner.com/learn/esp8266-microwave-motion-sensor-radar-sensor)  
📧 [Email](mailto:projectslearner@gmail.com)  
📸 [Instagram](https://www.instagram.com/projectslearner/)  
📘 [Facebook](https://www.facebook.com/projectslearner)  
▶️ [YouTube](https://www.youtube.com/@ProjectsLearner)  
📘 [LinkedIn](https://www.linkedin.com/in/projectslearner)

Created with ❤️ by ProjectsLearner