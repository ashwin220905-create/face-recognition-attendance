# face-recognition-attendance
Automated attendance system using real-time face recognition with OpenCV and Python. Short, clear, covers the tech stack.
# 🎓 Face Recognition Attendance System

## ✨ Features

- 🎥 **Real-time face detection** via webcam
- ✅ **Automatic attendance marking** with name, time, and date
- 📂 **CSV logging** — appends to `attendance.csv`
- ➕ **Easily scalable** — add a new person by dropping their photo in the folder

## 📋 Requirements
```bash
pip install opencv-python face_recognition numpy
```
> **Note:** `face_recognition` depends on `dlib`. On Windows, install CMake and Visual Studio Build Tools first.

## 📁 Project Structure
face-attendance/
├── images/
│   ├── Ashwin.jpg
│   ├── Priya.jpg
│   └── ...
├── attendance.csv
└── main.py
