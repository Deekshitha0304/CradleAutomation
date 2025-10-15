CradleAutomation

An Arduino-based Smart Cradle for automatic rocking and baby monitoring.

Overview

CradleAutomation is a smart cradle system designed to automatically rock a baby while monitoring environmental conditions such as sound, movement, temperature, and humidity. It helps parents ensure infant comfort and safety with minimal manual effort.

Features

Automatic cradle motion control using a servo motor.

Detection of sound and vibration for baby activity monitoring.

Temperature and humidity monitoring with real-time readings.

IoT integration for remote monitoring and alerts.

Mobile app integration for controlling the cradle and receiving notifications.

Hardware Components

Arduino Uno – Main microcontroller.

Servo Motor – Controls cradle rocking motion.

Sound Sensor – Detects baby’s crying or environmental noise.

Temperature & Humidity Sensor (DHT11) – Monitors room conditions.

Relay Module – Controls external devices if required.

Wi-Fi Module (ESP8266) – Enables IoT connectivity.

Software Requirements

Arduino IDE (latest version recommended)

Required libraries:

DHT sensor library

ESP8266WiFi library

How to Run

Open CradleAutomation.ino in Arduino IDE.

Connect your Arduino board via USB.

Ensure all hardware components are connected correctly.

Upload the code to the Arduino board.

Open the Serial Monitor to view real-time readings and cradle actions.

Future Enhancements

Advanced mobile app integration for control and monitoring.

Cloud-based data logging for analytics and historical tracking.

AI-based cry sound recognition to automate cradle response.

Author

Deekshitha Chinamuttevi

Repository

The project repository can be accessed at: https://github.com/Deekshitha0304/CradleAutomation
