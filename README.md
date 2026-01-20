Face Recognition Attendance System 🎓📸
Overview

The Face Recognition Attendance System is a real-time, AI-based application that automatically marks attendance using facial recognition.
Instead of manual registers or biometric devices, this system uses a webcam to recognize faces and record attendance in a CSV file with time stamps.

This project was developed as part of the Artificial Intelligence (UCS411) course at Thapar Institute of Engineering and Technology.

Problem Statement

Traditional attendance methods are:

Time-consuming

Prone to human errors

Easy to manipulate (proxy attendance)

Not hygienic (fingerprint scanners)

This project solves these issues by using computer vision and face recognition, providing a contactless, fast, and accurate attendance system.

Objectives

Automate the attendance process using face recognition

Eliminate proxy attendance

Reduce manual effort and errors

Provide real-time face detection and recognition

Store attendance records with timestamps

Create a scalable base for future enhancements

Technologies Used 🛠️
Component	Description
Language	Python 3
Libraries	OpenCV, face_recognition, NumPy
Input Device	Webcam
Output	CSV file (Attendance.csv)
IDE	VS Code / PyCharm
System Workflow ⚙️

Capture live video using a webcam

Detect faces in real time

Encode facial features (128-D vectors)

Compare live faces with stored images

Recognize known faces

Mark attendance with name and time in CSV

Avoid duplicate entries in the same session
