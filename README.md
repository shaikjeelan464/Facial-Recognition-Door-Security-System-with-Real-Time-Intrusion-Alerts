# Facial-Recognition-Door-Security-System-with-Real-Time-Intrusion-Alerts
Facial Recognition Door Security System using Raspberry Pi that enables secure access control by identifying authorized users. The system captures and processes images in real-time, unlocks the door on successful recognition, and triggers intrusion alerts with email notifications for unauthorized access or forced entry detection.

## 📌 Project Overview
This project implements a smart door security system using **facial recognition** and **real-time intrusion detection**. The system uses a Raspberry Pi to identify authorized users and control door access. If an unauthorized person attempts entry or forced access is detected, the system sends an alert via email.

---

## 🚀 Features
- 👤 Face Recognition-based Access Control  
- 🔓 Automatic Door Unlock for Authorized Users  
- ❌ Access Denied for Unauthorized Users  
- 📸 Real-time Image Capture  
- 🚨 Intrusion Detection using Vibration Sensor  
- 📧 Email Alerts with Captured Image  
- 🖥️ LCD Display Messages  
- ⏱️ Auto Door Closing  

---

## 🧠 System Workflow
1. User approaches the door  
2. Camera captures image  
3. Raspberry Pi processes the image  
4. Face recognition is performed  
5. If matched → Door unlocks & "Access Granted"  
6. If not matched → "Access Denied" + alert  
7. Vibration sensor detects forced entry  
8. Intrusion alert sent via email  

---

## 🏗️ System Architecture
- **Input:** Camera, Vibration Sensor  
- **Processing:** Raspberry Pi  
- **Output:** Servo Motor, LCD Display  
- **Storage:** Face Database (SD Card)  
- **Communication:** Email Alert System  

---

## 📊 Diagrams

### Use Case Diagram
![Use Case Diagram](USE%20CASE%20DIAGRAM.png)

### Activity Diagram
![Activity Diagram](Activity%20Diagram.png)

### Sequence Diagram
![Sequence Diagram](Sequence%20diagram.png)

### Collaboration Diagram
![Collaboration Diagram](Collobration%20diagram.png)

### Output Results
![WhatsApp Image 2026-04-21 at 2.49.30 PM](Test%20Image.png)

---

## 🛠️ Technologies Used
- Python  
- OpenCV  
- Face Recognition Library  
- Raspberry Pi  
- SMTP (Email Alerts)  

---

## 📦 Hardware Components
- Raspberry Pi  
- Pi Camera Module  
- Servo Motor  
- LCD Display  
- Vibration Sensor  
- Power Supply  

---

## 📽️ Demo Video
🔗 https://youtube.com/watch?v=8sIMcBIcFfc&feature=shared 
