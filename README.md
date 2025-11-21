# Android Object Detection (MobileNet TFLite)

An Android application for real-time object detection using a pre-trained **MobileNet** model converted to **TensorFlow Lite (TFLite)**.  
This app detects up to **1000 different object classes** from the ImageNet dataset and runs efficiently on mobile devices.

---

## 🚀 Features
- Real-time object detection on Android devices  
- Uses **MobileNet TFLite** (pre-trained model)  
- Fully implemented with **Java** on Android Studio  
- Clean and optimized frame processing pipeline  
- Lightweight & fast on mid-range devices  

---

## 🧠 Model Information
- Base model: **MobileNet** (provided by project owner / employer)  
- Converted to **TFLite** using Python only for compatibility  
- Final execution: **pure Java** on Android

---

## 📱 Tech Stack
- **Android Studio**
- **Java**
- **TensorFlow Lite**
- **MobileNet**
- **Python (model conversion only)**

---

## 📂 Project Structure
app/
├── java/
│ └── ... Object detection logic
├── assets/
│ └── mobilenet_model.tflite
└── res/
└── UI layouts



---

## 🎯 How It Works
1. Camera frames are captured in real-time  
2. Frames are preprocessed and fed into MobileNet TFLite  
3. Model outputs top object predictions  
4. Results are drawn on screen with confidence score  

---

## ▶️ How to Run
1. Clone the project:
https://github.com/mohammadjafarnia/Android-Object-Detection
2. Open in Android Studio  
3. Place the `.tflite` model into `assets/`  
4. Run on a real device (recommended)

---

## 👨‍💻 Developer
**Mohammad Hossein Jafarnia**  
Android Developer | ML Enthusiast  

GitHub:  
https://github.com/mohammadjafarnia

---

## ⭐️ Support
If you like this project, consider giving it a star ⭐️
