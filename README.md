<h1 align="center">🔥 Home Gas Safety System</h1>

<p align="center">
An IoT-based smart safety system that detects gas leaks, prevents hazards, and alerts users in real-time.
</p>

---

## 🏆 Achievement

🥇 **1st Prize Winner – IoT Exhibition**  
📍 GHRCEMP (GH Raisoni College of Engineering and Management, Wagholi)  
👨‍⚖️ Judged by faculty from **NIT Nagpur** and **IIT Goa**

---

## 🎥 Project Demo & Presentation

🔗 **Working Project Video**  
👉 https://drive.google.com/file/d/1gSTMltTgJrV9vck2xbrGrBWB1pPRgJzX/view?usp=sharing  

📊 **Project Presentation (PPT)**  
👉 https://docs.google.com/presentation/d/16K0k8Ys5x3OdZA3Cj57oqfRAvYdbZs5D/edit?usp=sharing&ouid=111146649149576739574&rtpof=true&sd=true  

---

## 🚀 Features

- 🚨 Automatically detects gas leaks and shuts off the gas supply  
- 📲 Sends real-time WhatsApp alerts via ThingESP  
- 🌐 Enables remote monitoring and control using IoT commands  
- 🏫 Improves safety and resource efficiency  

---

## 🧠 Technology Used

### 🔧 Hardware Components

| Component        | Purpose |
|-----------------|--------|
| **ESP32**       | Main microcontroller that processes sensor data and controls the system |
| **MQ6 Gas Sensor** | Detects gas levels (LPG, methane, etc.) |
| **Servo Motor** | Controls gas valve (open/close) |
| **Buzzer**      | Alerts with sound during gas leak |
| **LED**         | Indicates system status |
| **Breadboard & Wires** | Circuit connections |
| **Power Supply** | Powers the system |

---

### 🖼️ Project Image

<p align="center">
  <img src="https://github.com/user-attachments/assets/5f1ceb29-3266-4513-94c9-51d0efb6764f" width="400"/>
</p>

---

## 💻 Software & Tools

| Software / Library | Purpose |
|-------------------|--------|
| **Arduino IDE**   | Coding and uploading to ESP32 |
| **WiFi.h**        | Handles Wi-Fi connectivity |
| **ESP32Servo.h**  | Controls servo motor |
| **ThingESP.h**    | Enables WhatsApp communication |
| **Arduino.h**     | Core Arduino functions |
| **Serial Monitor**| Debugging tool |
| **Twilio API**    | WhatsApp messaging integration |
| **WhatsApp**      | User communication interface |

---

## ⚙️ Methodology

The system continuously monitors air using an MQ-series gas sensor connected to an ESP32.

### 🔄 Working Process:

1. 📡 Sensor detects gas concentration in real time  
2. ⚠️ If threshold exceeds:
   - 🔊 Buzzer activates  
   - 📲 WhatsApp alert is sent  
   - 🔒 Gas valve is automatically shut off  
3. 🧠 System prevents valve reopening until safe levels return  
4. 📱 Users can control system via WhatsApp commands:
   - `on`
   - `off`
   - `status`
   - `reset_alert`

✔️ Built with safety-first approach  
✔️ Includes rate-limiting to prevent message spam  
✔️ Fully programmed using Arduino IDE  

---

## 📊 Outcomes

- ✅ Successfully developed a working gas safety system  
- 🔍 Real-time gas leak detection implemented  
- 🔒 Automatic gas valve shutoff mechanism  
- 📲 WhatsApp-based alert system integrated  
- 🌐 Remote monitoring and control enabled  
- 🧪 Functional prototype demonstrated  

---

## 🎯 Key Benefits

- 🛡️ **Enhanced Safety** – Early detection prevents accidents  
- 📱 **Remote Monitoring** – Control system from anywhere  
- 💰 **Cost-Effective** – Affordable and scalable solution  
- ⚙️ **Automation** – Reduces human error  
- 🌐 **Smart Integration** – Fits into smart home ecosystem  
- 👨‍💻 **Learning Experience** – Hands-on IoT & embedded systems  

---

## 📚 References

1. ESP32 Documentation  
   👉 https://www.espressif.com/en/products/socs/esp32  

2. ThingESP Platform  
   👉 https://thingesp.com  

3. MQ Gas Sensor Datasheet  
   👉 https://www.sparkfun.com/datasheets/Sensors/Biometric/MQ2.pdf  

4. Arduino Documentation  
   👉 https://www.arduino.cc/reference/en  

5. ESP32 IoT Tutorials  
   👉 https://randomnerdtutorials.com/esp32-wi-fi  

6. Embedded Systems Journal (2023)  

7. Twilio WhatsApp API  
   👉 https://www.twilio.com/whatsapp  

---

## 👨‍💻 Contributors

- Satish Choudhary
- Jay Jadhav (https://github.com/jdjadhav)
- Vaibhav Tembukade (https://github.com/Vaibhav9T)
- Rahul Yadav
---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
