# ✋ Hand Gesture Recognition – Finger Count using MediaPipe

A simple project to recognize and count raised fingers from hand images using **Google Colab**, **MediaPipe**, and **OpenCV**.

## 🔍 Overview
This project uses static images of hands and:
- Detects hand landmarks using MediaPipe
- Counts the number of fingers raised
- Displays the result visually

## 🚀 Tech Stack
- Python
- MediaPipe
- OpenCV
- Google Colab

## 📁 Project Structure
finger_counter_project/
├── finger_counter_colab.ipynb
├── demo_images/
├── outputs/
├── requirements.txt
└── README.md

## 🧠 How it Works
1. MediaPipe detects 21 hand landmarks.
2. The relative position of fingers is used to count how many are raised.
3. Result is drawn on image and displayed.

## 🔧 How to Run
Open the notebook in [Google Colab](https://colab.research.google.com/) and follow the cells.

## 🎯 Future Work
- Extend to real-time video (on local Python script)
- Use it for gesture control applications

## 🙋‍♂️ Author
**Taha Malik**

---
