# Home-Gas-Safety-System
****************************************************************************************************************
• Automatically detects gas leaks and shuts off the gas supply.  • Sends real-time WhatsApp alerts via ThingESP.  • Provides remote monitoring and control through IoT commands.  • Enhances campus safety and resource efficiency
****************************************************************************************************************
IOT TECHNOLOGY
****************************************************************************************************************
Hardware Used: 
The following components are used in the model: 
Component Purpose 
ESP32 
Microcontroller 
Main controller that processes sensor data and manages 
system operations 
MQ6 Gas Sensor Detects gas levels in the environment  (e.g., LPG, 
methane) 
Servo Motor Controls the gas valve 
(opens/closes it based on gas detection) 
Buzzer Sounds a loud alarm when gas is detected 
LED Indicates system status (normal or alert) 
 Breadboard, Wires For circuit connections and prototyping 
Power Supply Provides necessary voltage to run the system components 

![IMG_8647](https://github.com/user-attachments/assets/5f1ceb29-3266-4513-94c9-51d0efb6764f)

****************************************************************************************************************
Software Used: 
****************************************************************************************************************
To program and operate the system, the following software tools are used: 
Software Purpose 
Arduino IDE 
 
.Platform used for coding and uploading programs to  
the ESP32 
 
.WiFi.h 
 
.Handles wireless connectivity between ESP32 and  
router 
 
.ESP32Servo.h 
 
.Controls the servo motor with precision 
 
.ThingESP.h 
 
.Enables WhatsApp communication and remote control  
via ThingESP cloud 
 
.Arduino.h 
 
.Core Arduino functions and syntax support 
 
.Serial Monitor 
 
.Real-time monitoring and debugging tool in the  
Arduino IDE 
 
.Twilio Twilio is a cloud communications platform that enables 
developers to build communication features like voice, 
text, chat, video, and email into their applications using 
APIs. Whatapp API integration for messaging. 
Whatsapp It used for communication with the user. The Arduino 
IDE is used for coding and uploading the firmware, 
while Twilio is used for real-time communication with 
the mobile app (Whatsapp)
****************************************************************************************************************
METHODOLOGY 
****************************************************************************************************************
Our system works by continuously monitoring the surrounding air for gas leaks using 
an MQ-series gas sensor. The sensor is connected to an ESP32 microcontroller, 
which reads the gas concentration levels in real time. If the gas level crosses a 
predefined safety threshold, the ESP32 triggers a series of automatic actions. 
First, the system activates a buzzer to provide an immediate audio alert to people 
nearby. At the same time, it sends an emergency WhatsApp message to a predefined 
phone number using the ThingESP platform. This ensures that the user is notified 
instantly, even if they are not physically present. 
To prevent further danger, the ESP32 also controls a servo motor that automatically 
turns off the gas valve. The system is designed with a safety-first approach — it will 
not allow the valve to open again until gas levels return to normal. 
Users can also interact with the system remotely using simple WhatsApp commands 
like "on", "off", "status", and "reset_alert". This remote control functionality allows 
users to check the status of the system and operate it safely from anywhere. 
The entire project is programmed and tested using the Arduino IDE. We used WiFi 
connectivity for seamless mobile integration, and implemented rate-limiting in the 
alert system to avoid message spamming. This makes the solution efficient, 
responsive, and user-friendly.
****************************************************************************************************************
OUTCOMES AND BENEFITS 
****************************************************************************************************************
Project Outcomes: 
• A functional Home Gas Safety System was successfully designed and 
implemented using ESP32, gas sensor, and servo motor. 
• The system can detect gas leaks in real-time and automatically shut off the 
gas valve to prevent hazards. 
• Integrated mobile notifications via WhatsApp using the ThingESP platform, 
enhancing user awareness and remote control. 
• Developed a working prototype capable of sound alerts, remote valve 
operation, and status monitoring. 
• Demonstrated the potential of IoT-based safety systems in household and 
commercial environments.
****************************************************************************************************************
Key Benefits: 
****************************************************************************************************************
• 🛡️ Enhanced Safety: Provides early gas leak detection and automatic 
emergency response, reducing the risk of fire or explosion. 
• 📱 Remote Monitoring: Allows users to check gas levels and control the gas 
valve from their phone, even when away from home. 
• 💰 Cost-Effective Solution: Built with affordable components, making it 
suitable for wide adoption in residential and small-scale industries. 
• ⚙️ 
Automation & Intelligence: Minimizes human intervention, reducing error 
and increasing reliability during emergencies. 
• 🌐 Smart Home Integration: Adds to the ecosystem of smart home devices, 
contributing to a safer, connected living space. 
• 👨‍💻 Learning Outcome: Gave the team hands-on experience with embedded 
systems, IoT platforms, and cloud-based communication.

****************************************************************************************************************
REFERENCES 
****************************************************************************************************************
1. Espressif Systems – ESP32 Technical Reference Manual Link: 
https://www.espressif.com/en/products/socs/esp32  
2. ThingESP Documentation – IoT Platform for ESP32 Integration 
Link: https://thingesp.com  
3. SparkFun Electronics – MQ Series Gas Sensor Datasheet (e.g., 
MQ-2) Link: 
https://www.sparkfun.com/datasheets/Sensors/Biometric/MQ
2.pdf  
4. Arduino – Official Programming Reference and Libraries Link: 
https://www.arduino.cc/reference/en  
5. Random Nerd Tutorials – ESP32 Wi-Fi Communication and IoT 
Projects Link: https://randomnerdtutorials.com/esp32-wi-fi  
6. Embedded Systems Journal (2023 Edition) – Buzzer and LED 
Indicators in Safety Systems 
7. Twilio – WhatsApp Messaging API for IoT Alerts Link: 
https://www.twilio.com/whatsap
