# Face Recognition Attendance System

## Overview
The Face Recognition Attendance System is a Python-based application that utilizes computer vision and deep learning techniques to automate the attendance marking process. It captures images of individuals and recognizes them in real-time, allowing for efficient and accurate attendance tracking.

## Features
- **Real-time Face Recognition**: Captures live video feed and recognizes faces.
- **Attendance Marking**: Automatically marks attendance based on recognized faces.
- **Sample Capture**: Captures and stores multiple samples of each individual for accurate recognition.
- **User-friendly Interface**: Built using `tkinter` for a simple and intuitive experience.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - OpenCV: For image processing and face detection.
  - Haar Cascade: For frontal face detection.
  - `tkinter`: For creating the GUI.
  - SQL: For storing and managing attendance records.
  - NumPy: For numerical operations.
  
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ganeshagrahari/Face-Recognition-Attendance-System.git
   cd Face-Recognition-Attendance-System
  
Here's a sample README file content for your Face Recognition Attendance System GitHub repository. You can customize it as needed:

markdown
Copy code
# Face Recognition Attendance System

## Overview
The Face Recognition Attendance System is a Python-based application that utilizes computer vision and deep learning techniques to automate the attendance marking process. It captures images of individuals and recognizes them in real-time, allowing for efficient and accurate attendance tracking.

## Features
- **Real-time Face Recognition**: Captures live video feed and recognizes faces.
- **Attendance Marking**: Automatically marks attendance based on recognized faces.
- **Sample Capture**: Captures and stores multiple samples of each individual for accurate recognition.
- **User-friendly Interface**: Built using `tkinter` for a simple and intuitive experience.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - OpenCV: For image processing and face detection.
  - Haar Cascade: For frontal face detection.
  - `tkinter`: For creating the GUI.
  - SQL: For storing and managing attendance records.
  - NumPy: For numerical operations.
  
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ganeshagrahari/Face-Recognition-Attendance-System.git
   cd Face-Recognition-Attendance-System
2.Install the required libraries:

bash
Copy code
pip install opencv-python numpy
Ensure that you have a webcam connected to your computer.

3.Usage
Run the application:
bash
Copy code
python main.py
Follow the on-screen instructions to capture samples and mark attendance.
How It Works
Capture Samples: The system captures 100 samples of a particular person and stores them as an array.
Face Detection: Using Haar Cascade, the application detects faces in the camera feed.
Recognition: The captured samples are matched with the live feed to recognize individuals.
Attendance Logging: Recognized individuals are logged into the attendance record.
Screenshots

4.Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or features you'd like to add.

5.License
This project is licensed under the MIT License - see the LICENSE file for details.

6.Acknowledgments
OpenCV team for their powerful computer vision library.
Contributors and developers of the libraries used in this project.
Contact
For any questions or feedback, feel free to reach out to me:

Email: ganeshagrahari108@gmail.com

### Notes:
- You can modify the contact information or add any additional sections based on your preferences.
- Make sure to update any placeholders, like screenshots, to match your actual repository content.
