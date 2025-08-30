# 👆 Hand Gesture Swipe Control

    Control your keyboard arrow keys using hand gestures captured by a webcam!
    This project uses OpenCV, Mediapipe, and PyAutoGUI to detect index finger swipes and trigger arrow key presses (Up, Down, Left, Right).


# ✨ Features

    Real-time hand tracking using Mediapipe

    Detects index finger swipe gestures:

    Swipe Left → Press Right Arrow

    Swipe Right → Press Left Arrow (intentionally inverted in code)

    Swipe Up → Press Up Arrow

    Swipe Down → Press Down Arrow

    Cooldown timer to prevent multiple accidental triggers

    Visual feedback: detected landmarks & gesture name shown on screen


# 🛠️ Tech Stack

    Python 3.12

    OpenCV – for webcam input & visualization

    Mediapipe – for real-time hand landmark detection

    PyAutoGUI – for simulating keyboard key presses


# 📦 Installation

## Clone this repository:

    git clone https://github.com/akashdixit05/Gesture-Based-Arrow-Key-Control-Project.git
    cd hand-gesture-swipe-control


## Install dependencies:

    pip install opencv-python mediapipe pyautogui


## Run the script 

    python handgame.py

## Controls

    Move index finger horizontally → Triggers Left/Right arrow keys

    Move index finger vertically → Triggers Up/Down arrow keys

    Press ESC → Exit the program



# How It Works

    Captures webcam frames with OpenCV

    Uses Mediapipe to detect hand landmarks

    Tracks the index fingertip (landmark 8)

    Compares current vs last position to detect swipes

    Simulates key presses with PyAutoGUI

# Author
Akash Dixit
