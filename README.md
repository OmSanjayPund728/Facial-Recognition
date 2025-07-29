# Facial-Recognition
🔒 AI-Based Facial Recognition Security System
This project is a low-cost, AI-powered facial recognition security system designed to detect and differentiate between authorized and unauthorized individuals in real time. It uses a webcam connected to a computer running a face recognition model (built with Python, OpenCV, and face_recognition library), and interfaces with an STM32 (Blue Pill) microcontroller to manage physical security responses such as LED indicators and sensor integration.

💡 Features
Real-time face detection and recognition

Automatic identification of unauthorized individuals

UART communication between PC and STM32

PIR & IR sensors for motion and proximity detection

Visual feedback using LED indicators

Low hardware cost and scalable architecture

🛠️ Technologies Used
Python 3.10

OpenCV

face_recognition

dlib

STM32 (Blue Pill) with UART communication

Hardware sensors: PIR, IR, LEDs

🖥️ How It Works
Webcam captures live video feed.

Python script processes frames, detects faces, and checks them against an authorized database.

If the face matches, "Authorized" signal is sent via UART to STM32.

STM32 activates green LED; otherwise, red LED indicates denial.

PIR/IR sensors add an extra security layer by detecting motion/presence.

📦 Components Required
USB Webcam

STM32F103C8T6 (Blue Pill)

PIR Sensor, IR Sensor

Red & Green LEDs

Jumper wires & USB-to-UART converter (if needed)
