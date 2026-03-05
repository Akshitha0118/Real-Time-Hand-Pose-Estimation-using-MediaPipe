# 🖐️ Real-Time Hand Landmark Detection System

A real-time multi-hand landmark detection system built using **MediaPipe** and **OpenCV**.  
This project detects and tracks 21 hand landmarks per hand from video input and automatically saves the annotated output video.

---

## 📌 Features

- ✅ Multi-hand detection
- ✅ 21-point landmark tracking per hand
- ✅ Real-time video processing
- ✅ Automatic output video saving
- ✅ Clean and optimized implementation

---

## 🛠️ Tech Stack

- Python 3.10
- OpenCV
- MediaPipe
- TensorFlow
- NumPy

---

## 🧠 How It Works

Frames are captured from the input video.

Each frame is converted from BGR to RGB.

MediaPipe Hands model processes the frame.

21 landmark points are detected per hand.

Landmarks are drawn on the frame.

The processed frame is saved to output video.
