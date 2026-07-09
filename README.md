# 📡 WiSense AI

### *Privacy-First Human Sensing using WiFi & Edge AI*

> **Transform an ordinary WiFi network into an intelligent, camera-free human sensing system using ESP32 and AI.**

![License](https://img.shields.io/badge/License-MIT-green.svg)
![ESP32](https://img.shields.io/badge/Hardware-ESP32-blue)
![Python](https://img.shields.io/badge/Python-3.10+-yellow)
![AI](https://img.shields.io/badge/Edge-AI-red)
![Status](https://img.shields.io/badge/Status-Under%20Development-orange)

---

# 🚀 Overview

**WiSense AI** is an open-source Edge AI project that leverages **WiFi Channel State Information (CSI)** to detect and understand human activities **without cameras or wearables**.

Instead of capturing images, the system analyzes how WiFi signals change as they interact with people and objects. By applying AI models to CSI data collected from an **ESP32**, WiSense AI can recognize human presence, activities, breathing patterns, and more—all while preserving privacy.

> **"Your WiFi isn't just for internet anymore—it's a sensor."**

---

# ✨ Features

### 🟢 Human Presence Detection

Detect whether a person is present in a room.

### 🚶 Activity Recognition

Recognize activities such as:

* Walking
* Sitting
* Standing
* Waving
* Falling
* Idle

---

### ❤️ Contactless Vital Monitoring *(Experimental)*

Estimate

* Breathing Rate
* Heart Rate

using WiFi signal reflections.

---

### 🧍 Human Pose Estimation *(Research)*

Estimate body posture using radio signals instead of cameras.

---

### 🏠 Smart Room Monitoring

Detect

* Furniture movement
* Room occupancy
* Environmental changes

---

### 🔒 Privacy First

Unlike cameras,

✅ No images

✅ No facial recognition

✅ No video recording

Only anonymous WiFi signal analysis.

---

# 🧠 How It Works

```
              WiFi Router
                    │
                    │
          WiFi Radio Signals
                    │
                    ▼
          Human / Object Movement
                    │
                    ▼
         Signal Reflection Changes
                    │
                    ▼
        ESP32 captures CSI packets
                    │
                    ▼
        Feature Extraction Pipeline
                    │
                    ▼
         Machine Learning Model
                    │
                    ▼
     Presence / Activity Prediction
```

---

# 🛠 Hardware

* ESP32 (CSI Supported)
* WiFi Router
* Laptop / Raspberry Pi
* USB Cable

Optional

* OLED Display
* Buzzer
* Relay Module
* MQTT Server

---

# 💻 Software Stack

### Embedded

* ESP-IDF
* ESP32 CSI Firmware

### AI

* Python
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / PyTorch

### Visualization

* Streamlit
* Matplotlib
* OpenCV (optional)

---

# 📂 Project Structure

```
WiSense-AI
│
├── firmware/
│   ├── esp32_csi/
│   └── data_logger/
│
├── dataset/
│   ├── walking/
│   ├── sitting/
│   ├── standing/
│   ├── empty_room/
│   └── fall/
│
├── models/
│   ├── presence_model/
│   ├── activity_model/
│   └── breathing_model/
│
├── scripts/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│   └── visualize.py
│
├── dashboard/
│
├── docs/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

# 📈 AI Pipeline

```
ESP32

↓

Capture CSI

↓

CSV Dataset

↓

Signal Processing

↓

Feature Extraction

↓

Model Training

↓

Real-Time Prediction

↓

Dashboard
```

---

# 🎯 Roadmap

## Phase 1

* [x] CSI Data Collection
* [x] Live Signal Visualization
* [ ] Human Presence Detection

---

## Phase 2

* [ ] Activity Recognition
* [ ] Occupancy Counting
* [ ] Smart Room Detection

---

## Phase 3

* [ ] Fall Detection
* [ ] Breathing Monitoring
* [ ] Heart Rate Estimation

---

## Phase 4

* [ ] Pose Estimation
* [ ] TinyML Deployment
* [ ] Raspberry Pi Edge Server

---

# 📊 Applications

🏠 Smart Homes

🏥 Healthcare Monitoring

🤖 Robotics

🏢 Smart Offices

🔒 Security Systems

👵 Elderly Care

📦 Warehouse Monitoring

🚗 Smart Parking

---

# 📸 Future Demo

```
Status

🟢 Human Detected

Activity

🚶 Walking

Confidence

98.2%

Breathing

16 BPM

Heart Rate

74 BPM
```

---

# 🧪 Dataset

The AI model is trained using CSI data collected from an ESP32.

Example labels

```
walking.csv

standing.csv

empty.csv

sitting.csv

fall.csv

breathing.csv
```

---

# 📚 Machine Learning Models

Current

* Random Forest
* SVM
* XGBoost

Future

* CNN
* LSTM
* Transformer
* TinyML Models

---

# 🔥 Future Integrations

* 🤖 Robot Companion
* 🏠 Home Automation
* 📱 Mobile Notifications
* ☁️ Cloud Dashboard
* 📡 MQTT Integration
* 🧠 Edge AI Deployment
* 🎙 Voice Assistant
* 🛸 Autonomous Robots

---

# 🌟 Why WiSense AI?

✔ Camera-Free

✔ Privacy Preserving

✔ Low Cost

✔ Open Source

✔ Real-Time

✔ Edge AI Powered

✔ Scalable

✔ Research Friendly

---

# 📖 References

* ESP32 CSI Documentation
* IEEE WiFi Sensing Research Papers
* TensorFlow Lite
* TinyML
* Channel State Information Research

---

# 🤝 Contributing

Contributions are always welcome!

Feel free to

* Fork the repository
* Create a feature branch
* Submit a Pull Request
* Open Issues
* Suggest Improvements

---

# 👨‍💻 Author

## **Aditya Kushwaha**

**AI • Robotics • IoT • Embedded Systems**

> *Building intelligent systems that interact with the world through wireless sensing and Edge AI.*

---

# ⭐ Support

If you find this project useful,

⭐ **Star the repository**

🍴 **Fork it**

📢 **Share it with the community**

---

## 🚀 Vision

> **"The future of sensing isn't just about cameras—it's about understanding the invisible. WiSense AI transforms everyday WiFi into an intelligent, privacy-preserving sensor, bringing Edge AI, wireless sensing, and robotics together to redefine how machines perceive the world."**
