# 🎯 Realtime Vision App

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Framework-Streamlit-ff4b4b.svg)](https://streamlit.io/)  
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green.svg)](https://github.com/ultralytics/ultralytics)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A real-time object detection dashboard built using **YOLOv8** and **Streamlit**.  
It allows you to upload images/videos or use your webcam for instant detections with a clean and interactive UI.

---

## 📸 Demo

👉 *Replace with your own screenshots/GIFs*  

![App Screenshot]<img width="1918" height="834" alt="Screenshot 2025-09-16 201405" src="https://github.com/user-attachments/assets/d7263c43-999c-49e5-8452-c4383dae0a74" />

)  
*Example: Webcam detection running with YOLOv8*  

![Demo GIF](assets/demo.gif)  
*Example: Live video detection pipeline*

---

## ✨ Features
- 📷 Upload **images** → get instant detection results  
- 🎞️ Upload **videos** → bounding boxes over frames  
- 🎦 Use **webcam** → real-time object detection  
- ⚡ Powered by **YOLOv8** (Ultralytics) for speed and accuracy  
- 🎨 Interactive UI built with **Streamlit**  
- 📊 View detection **classes & confidence scores**

---

## 🛠️ Installation

Clone the repo and set up the environment:

```bash
git clone https://github.com/arushimathur2604/Realtime-Vision-App.git
cd Realtime-Vision-App

# Create & activate virtual environment (Windows)
python -m venv .venv
.\.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
