# Home-Automation using ESP32 with Google home

This project implements a smart home automation system using the ESP32 microcontroller and Google Home. Control various home appliances through voice commands via Google Home with a highly customizable and cost-effective setup.

KEY FEATURE:
Voice Control: Operate home appliances using Google Home voice commands.

ESP32 Integration: Utilizes the ESP32 microcontroller for Wi-Fi-based control of devices.

Real-Time Monitoring: Check the status of connected devices in real-time.

Customizable Setup: Tailor the system to your specific needs and appliances.

Cost-Effective: Affordable solution using readily available components.

SYSTEM ARCHITECTURE:

ESP32: Central hub for controlling connected devices.

Google Home: Interface for issuing voice commands.

Wi-Fi Communication: Ensures seamless connectivity between ESP32 and Google Home.

Web Interface (Optional): Provides manual control and monitoring via a web browser.

SETUP AND INSTALLATION:

1. Install the Arduino IDE
Download and install the Arduino IDE from the Arduino website.

2. Configure Arduino IDE for ESP32
Open Arduino IDE.
Update Preferences:
Go to File -> Preferences.
In the Additional Boards Manager URLs field, add the following URLs:
bash
Copy code
https://dl.espressif.com/dl/package_esp32_index.json
http://arduino.esp8266.com/stable/package_esp8266com_index.json
Install ESP32 Board:
Go to Tools -> Board -> Boards Manager.
Search for "ESP32" and click "Install" for the ESP32 board package.

3. Download Required Libraries

Sinric Pro:
Download the Sinric Pro library for ESP8266 & ESP32 from Sinric Pro GitHub.

WebSockets:
Install the WebSockets library (minimum version 2.3.5) from the Library Manager:
Go to Sketch -> Include Library -> Manage Libraries.
Search for "WebSockets" and install the latest version (minimum 2.3.5).

ArduinoJson:
Install the ArduinoJson library (minimum version 6.12.0) from the Library Manager:
Go to Sketch -> Include Library -> Manage Libraries.
Search for "ArduinoJson" and install version 6.12.0 or later.

4. Program the ESP32
Connect the ESP32 to your computer using a USB cable.
Select the appropriate board and port:
Go to Tools -> Board and select "ESP32 Dev Module" (or your specific ESP32 model).
Go to Tools -> Port and select the COM port associated with your ESP32.
Upload the Code:
Open the provided example code or your own code in the Arduino IDE.
Click the "Upload" button to compile and upload the code to the ESP32.
Wait for the upload process to complete and ensure there are no errors.
Usage
After programming the ESP32, follow these steps to integrate with Google Home:

CONFIGURE OF ESP32:
Adjust the settings in the code to match your Wi-Fi credentials and Google Home integration details.

ADD TO GOOGLE HOME:
Use the Google Home app to add the ESP32 as a new device.
Follow the instructions in the app to configure voice commands for controlling your appliances.

FUTURE ENHANCEMENT:
Integrate with other smart home ecosystems (e.g., Amazon Alexa).
Expand functionality to include additional sensors and automation features.
Develop a dedicated mobile app for enhanced control and scheduling.
