#  Zoom In & Zoom Out using Hand Gestures
This project uses **OpenCV** and **cvzone** to zoom in/out on an image using a **two-hand pinch gesture** involving just the **thumb and index fingers**, captured via a **laptop webcam**.
## Features
- Real-time hand tracking using your **laptop camera**
- Gesture detection with **thumb and index fingers only** ([1, 1, 0, 0, 0])
- Dynamically zooms an image (`boo.jpg`) based on distance between fingertips
- Simple and interactive — no need for mouse or keyboard

## Requirements

Install dependencies:
- pip install cvzone
- pip install mediapipe
