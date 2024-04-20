# Web-Based Facial Authentication System
![Blue Modern Gaming Banner Landscape](https://github.com/hyba-ab/Cyber-security-Project-Facial-Recognition-based-Attendance-System/assets/164689889/34eaa438-f6a6-4758-83e8-2b3f0371f099)
## Introduction
This project explores the development of a web-based facial authentication system, leveraging facial recognition technology to enhance security and streamline user verification processes.
## Project Goals
- Enhanced Security: Integrate facial recognition technology into existing security infrastructure for robust user identification.
- Streamlined User Verification: Provide a convenient and efficient alternative to traditional password-based authentication methods.
- Scalability and Flexibility: Design a system that can adapt to various use cases and security requirements.
## Technical Overview
The system is designed as a web application with two components:
- ### Desktop Application (Optional):
  - Client-server architecture for capturing images, handling user interactions, and processing facial recognition tasks on the server.
  - Python for backend development.
  - OpenCV for face detection and recognition functionalities.
- ### Web Application:
  - Flask web framework for building and serving the web interface.
  - HTML, CSS, and Bootstrap for user interface design and responsiveness.
  - OpenCV (cv2) for capturing webcam video, face detection, and recognition.
  - Machine learning model (K-Nearest Neighbors) trained on facial images for recognizing 
   users.
  - Python for backend development.
  - NumPy for numerical computing.
  - Scikit-learn for implementing the KNN algorithm.
  - Pandas for data manipulation and handling CSV files for attendance records.
  - Joblib for saving and loading the machine learning model.
## Functionalities
 - ### User Management:
 Enroll users by capturing their facial images and storing them in a secure database.
 - ### Attendance Management (Web Application):
     - Capture video from the webcam.
     - Detect faces in real-time.
     - Recognize users based on the trained facial recognition model.
     - Record attendance for identified users.
     - Store attendance data in CSV files.
 - ### Login (Desktop Application):
     - Capture an image from the webcam.
     - Send the image to the server for processing.
     - Perform face detection and recognition on the server.
     - Verify the user's identity based on stored facial encodings.
     - Grant access upon successful verification.

## Getting Started : 
#### 1.Prerequisites: 
   Ensure you have Python, OpenCV, Flask, NumPy, Scikit-learn, Pandas, and Joblib installed on your development environment.
#### 2.Clone the Repository: 
   Clone this repository using git clone [Link](https://github.com)
#### 3.Set Up Environment: (Optional for Desktop Application) 
   Create a virtual environment to manage project dependencies:



