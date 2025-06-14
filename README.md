# 👕 SMART ASSISTIVE CLOTHING

## 🧠 Project Overview

**Smart Assistive Clothing** is a wearable safety and support system designed for elderly individuals, people with disabilities, and patients under rehabilitation. The system uses real-time location tracking, motion sensing, and intelligent alerts to notify caregivers in case of abnormal movement or emergencies.

This project integrates a GPS module, gyroscope, and Arduino microcontroller into a coat, powered by a rechargeable battery. Alerts are sent via Telegram (with location), Blynk app (with sound), and email. An embedded LED also provides a visual indicator directly on the coat.

---

## 🎯 Objectives

- Ensure the **safety and security** of the user by detecting falls or abnormal motion
- Enable **location-based alerts** to caregivers in case of an emergency
- Provide **multi-channel notifications**: visual (LED), audio (Blynk), and digital (Telegram, Email)
- Offer a **wearable and non-intrusive** solution with simple daily usability

---

## 🧩 Key Features

- ✅ **GPS Tracking**: Sends real-time location upon critical events (fall or help request)
- ✅ **Gyroscope**: Detects unusual motion or falls using angular movement data
- ✅ **LED Indicator**: Visual alert embedded in the coat when triggered
- ✅ **Multi-Channel Notifications**:
  - 📍 **Telegram Bot**: Sends a message with live Google Maps location
  - 🔊 **Blynk App**: Sends app notification with sound
  - 📧 **Email Alert**: Sends emergency email to preset contacts
- ✅ **Rechargeable Battery**: Ensures portability and long-term use
- ✅ **Arduino Powered**: Easy to prototype and cost-efficient

---

## 🛠️ Hardware Components

| Component             | Description                                 |
|----------------------|---------------------------------------------|
| Arduino UNO / Nano   | Microcontroller unit                        |
| GPS Module (NEO-6M)  | To get real-time location                   |
| MPU6050 Gyroscope    | For motion and fall detection               |
| LED                  | For visual indication inside coat           |
| Rechargeable Battery | Li-ion or 9V battery with power bank module |
| Buzzer (optional)    | For audible alert (if not using Blynk)      |
| Wi-Fi Module (ESP8266) or GSM Module | For communication features     |

---

## 📲 Software Features

- **Arduino IDE**: Code for sensor integration and logic
- **Telegram Bot API**: Sends location-based messages
- **Blynk IoT Platform**: Sends push notifications with sound
- **SMTP Protocol / IFTTT**: For sending emails

---

## 🔁 Workflow Diagram

![Screenshot 2025-06-14 102037](https://github.com/user-attachments/assets/15036ca1-6eda-4b56-820f-a914cf61070b)




---

## 🔧 Sample Use Case

> 👵 An elderly person wearing the coat falls.  
> ➤ The gyroscope detects abnormal acceleration.  
> ➤ GPS module reads current coordinates.  
> ➤ Arduino sends:
> - 📍 Telegram message with a Google Maps link  
> - 🔊 Blynk app alert with sound  
> - 📧 Email to emergency contact  
> ➤ LED on the coat turns ON to alert nearby people

---

## 🚀 Future Enhancements

- Add **voice command trigger** or panic button
- **Battery level monitoring** via app
- **Machine Learning** to reduce false fall detections
- Integration with **emergency services**

---

