README FILE
# 🚀 Real-Time Object Detection and Classification System

## 📌 Project Overview
This project implements a **real-time object detection and classification system** using **YOLO (You Only Look Once)** optimized for **edge devices** like Raspberry Pi. The system captures live video, detects objects, tracks them, and can trigger alerts such as email notifications.

It is designed for **low-power, real-time applications** such as surveillance, smart monitoring, and automation.

---

## 🎯 Objectives
- Perform real-time object detection using YOLO model
- Deploy model on edge device (Raspberry Pi)
- Optimize performance for low latency
- Integrate object tracking system
- Enable alert system (email notifications)

---

## 🛠️ Technologies Used

### 💻 Software
- Python
- OpenCV
- NumPy
- ONNX Runtime
- PyTesseract (for OCR if needed)

### 🔧 Hardware
- Raspberry Pi 4
- Raspberry Pi Camera Module (5MP)
- SD Card (32GB or higher)
- Display (optional)

### 📦 Libraries
- cv2
- numpy
- onnxruntime
- pytesseract
- smtplib

---

## ⚙️ System Architecture

1. Capture live video using Pi Camera  
2. Preprocess frames  
3. Run YOLO model (ONNX format)  
4. Detect objects with bounding boxes  
5. Track objects across frames  
6. Trigger alerts if required  
7. Display output in real-time  

---

## 🔄 Workflow

1. **Input**: Live camera feed  
2. **Processing**:
   - Frame extraction
   - Object detection (YOLO)
   - Object tracking  
3. **Output**:
   - Detected objects with labels
   - Alerts (email notifications)

---

## 📊 Features
- Real-time object detection
- Lightweight YOLO model (optimized for edge)
- Object tracking support
- Email alert system
- Easy deployment on Raspberry Pi

---

## 🧠 Model Details
- Model: YOLO (ONNX format)
- Inference Engine: ONNX Runtime
- Input Size: Depends on model (e.g., 640x640)
- Performance: Optimized for edge devices

---

## 📥 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name