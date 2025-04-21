# Navdristi: Advanced Cognitive Companion System (ACCS)

**Navdristi** is an intelligent assistive navigation system designed for visually impaired users, enabling safe and accurate indoor mobility using real-time object detection, RSSI-based trilateration, and voice feedback.

> Developed using ESP32, ESP32-CAM, mobile integration, and lightweight AI.

---

## 🔍 Features

- 📸 **Object Detection** via ESP32-CAM (MobileNET v2)
- 📶 **Trilateration-based Indoor Positioning** using RSSI from multiple Beacons
- 📱 **Real-time Navigation Feedback** on a mobile device via voice
- 🔊 **Voice Feedback System** for path guidance and obstacle alerts
- 🔧 **Modular Architecture** with multi-device integration (ESP32 & Mobile)

---

## 🧠 System Architecture


- **ESP32-CAM**: Detects objects in the user's path, sends metadata also recives  BLE signals, calculate RSSI
- **Mobile Device**: Computes user's position, generates navigation commands, and delivers voice feedback

---

## ⚙️ Tech Stack

- **Hardware:** ESP32, ESP32-CAM, HM-10 BLE modules
- **Programming:** C++ (Arduino), Python (for visualization)
- **AI/ML:** TensorFlow Lite Model on ESP32-CAM
- **Communication:** UART, BLE, Wi-Fi 
- **Mobile Integration:** Android App with MIT inventor

---

### 1. Clone the Repository

```bash
download folder ESP_inferencing 
cd to your ardunio ide folder
download CODE.ino file
Run it on ardunio ide 
