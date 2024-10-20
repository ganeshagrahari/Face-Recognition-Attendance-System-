# Face-Recognition-Attendance-System-

## Overview
The **Face Recognition Attendance System** is an automated solution for managing attendance using facial recognition technology. Built using **Python**, this system employs **OpenCV** for real-time face detection, a **Convolutional Neural Network (CNN)** for face recognition, and provides a user-friendly interface using **ttkinter**. It captures multiple face samples, processes them, and records attendance when a match is detected through the camera.

## Features
- **Graphical User Interface (GUI)**: Created with `ttkinter` for an easy and intuitive user experience.
- **Face Detection**: Uses OpenCV with Haar Cascade to detect faces in real-time video streams.
- **Face Registration**: Captures 100 samples of a person's face and converts them into arrays for training.
- **Face Recognition**: Uses a CNN model to match the live camera feed with registered face data.
- **Attendance Management**: Automatically logs attendance data in an SQL database when a registered face is recognized.
- **Data Export**: Attendance records can be exported into an Excel file for further analysis.

## Technologies Used
- **Python**: For building the core logic and algorithms.
- **ttkinter**: For developing the graphical user interface.
- **OpenCV**: For video capture and face detection.
- **CNN (Convolutional Neural Network)**: For training and recognizing faces.
- **SQL**: For managing user data and attendance records.
- **Excel**: To export attendance data for record-keeping.
- **Haar Cascade**: For detecting faces during the recognition process.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ganeshagrahari/Face-Recognition-Attendance-System-.git
   cd Face-Recognition-Attendance-System-
