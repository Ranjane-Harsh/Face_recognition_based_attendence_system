# Face Recognition and Attendance System

This project implements a face recognition-based attendance system using real-time webcam video feed. The system allows users to login, logout, and register new users using facial recognition. It integrates an anti-spoofing mechanism to ensure accurate identification and prevent fraud. 

## Features

- **Login/Logout:** Users can log in and out by facing the webcam. The system records attendance with timestamps in a log file.
- **Real-time Video Feed:** A webcam captures live video, and frames are processed for face recognition.
- **User Registration:** New users can register by providing their face data, which is stored for future recognition.
- **Anti-Spoofing:** Prevents unauthorized access using anti-spoofing models.

## Dependencies

- OpenCV
- Tkinter
- face_recognition
- PIL (Pillow)
- Custom utility functions (util.py)

## How It Works

1. **Webcam Feed:** Captures real-time video feed.
2. **Face Recognition:** Detects faces in the frame and compares them to stored embeddings in the database.
3. **User Registration:** Encodes and saves facial data using the `face_recognition` library.
4. **Attendance Logging:** Logs login/logout events with timestamps.


