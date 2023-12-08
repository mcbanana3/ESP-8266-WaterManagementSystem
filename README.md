**ESP-8266 Water Level Monitoring and Control System**

**Owner:** Aryan Yalavarthi

**Overview:**
This repository contains the codebase for a water level monitoring and control system using ESP-8266 modules. The system employs ultrasonic sensors to measure water levels at a specific site. If the water level surpasses a defined threshold, the ESP-8266 module initiates a series of actions, including controlling a servo motor and notifying the user via SMS without the need for a GSM module. Additionally, the system utilizes IFTTT webhooks to send messages and illuminate an LED when the water level exceeds 30 units.

![Sender-ESP-DIAGRAM](https://github.com/mcbanana3/ESP-8266/assets/146920196/5474a119-c7e9-4be6-9706-3634cabc36ed)

**Key Features:**
- **Ultrasonic Sensor Integration:** Measures water levels accurately using ultrasonic sensors connected to an ESP-8266 module.
- **Remote Servo Motor Control:** Controls a servo motor over the internet to manage water flow or gates based on water level conditions.
- **SMS Notification Without GSM:** Sends SMS notifications to the user's phone without the need for a GSM module, leveraging IFTTT webhooks.
- **IFTTT Integration:** Utilizes IFTTT webhooks to trigger events such as sending messages and lighting up an LED when the water level rises above 30 units.
- **Clean and Modular Codebase:** Well-organized code with comments for easy understanding and modification.

![image](https://github.com/mcbanana3/ESP-8266/assets/146920196/abb162bf-d552-490f-9e83-a0d8fbac18fd)

**Repository Structure:**
- **/src:** Contains the source code for ESP-8266 modules.
  - **/ultrasonic_sensor_module:** Code for reading data from the ultrasonic sensor.
  - **/servo_control_module:** Code for controlling the servo motor based on water level conditions.
  - **/ifttt_integration:** Integration with IFTTT webhooks for SMS notification and LED control.
- **/hardware_diagrams:** Schematics and diagrams illustrating the hardware connections.

![image](https://github.com/mcbanana3/ESP-8266/assets/146920196/08527158-f01a-4234-89e3-d481b623ccf1)

**Getting Started:**
1. Clone the repository to your local machine.
2. Set up the ESP-8266 modules with the necessary connections as per the provided diagrams.
3. Configure the system parameters and Wi-Fi credentials in the code.
4. Flash the code to the ESP-8266 modules using the Arduino IDE or your preferred platform.
5. Monitor water levels and observe the system's actions based on the defined thresholds.

![Reciever-ESP-Diagram](https://github.com/mcbanana3/ESP-8266/assets/146920196/2a953a29-5d7f-4ad3-9ce1-5d512c4ce0bb)

**Note:**
Ensure proper safety precautions and adherence to local regulations when deploying the system. This project serves as a starting point and can be extended for specific use cases.

Feel free to contribute, report issues, or suggest improvements to enhance the functionality of the water level monitoring and control system.

---
