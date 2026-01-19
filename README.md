# 🕺 Holistic Motion Capture & Keypoint Engine
> **1st Prize Winner @ SRM 48-Hour Hackathon** > A high-performance PyQt5 application for real-time skeletal, facial, and hand landmark extraction using MediaPipe.

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![MediaPipe](https://img.shields.io/badge/AI-MediaPipe_Holistic-00C853.svg)](https://mediapipe.dev/)
[![PyQt5](https://img.shields.io/badge/GUI-PyQt5-90caf9.svg)](https://www.riverbankcomputing.com/software/pyqt/)
[![Award](https://img.shields.io/badge/Award-1st_Place_Hackathon-gold.svg)]()

## 📌 Project Overview
This system was developed to solve the challenge of high-latency motion capture. By integrating **Google MediaPipe's Holistic model** with a custom **PyQt5** dashboard, the application provides a seamless way to track, visualize, and record 540+ individual keypoints across the human body, face, and hands in real-time.



## ✨ Key Features
* **Real-time Holistic Tracking:** Unified processing of pose, face mesh, and hand landmarks.
* **Selective Part Optimization:** Toggle between "Whole Body", "Face", "Hands", or "Legs" to optimize processing speed.
* **Data Serialization:** Record motion sequences and export them as structured **JSON** for use in 3D animation (Unreal Engine) or ML model training.
* **Professional GUI:** Built with PyQt5, featuring live camera feeds, dynamic mode switching, and secure recording controls.

## 🛠️ Tech Stack
* **Core Logic:** Python, OpenCV, MediaPipe
* **Desktop Framework:** PyQt5
* **Data Handling:** JSON, NumPy
* **Logging:** Integrated Python Logging for real-time monitoring.

## 🚀 Getting Started

### Prerequisites
* Python 3.9 or higher
* A webcam

### Installation
1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/yourusername/Skeletal-Tracking.git](https://github.com/yourusername/Skeletal-Tracking.git)
   cd Skeletal-Tracking
2. **Install Dependencies:**
   It is recommended to use a virtual environment. Install the required libraries using pip:
   ```bash
   pip install opencv-python mediapipe PyQt5 numpy
