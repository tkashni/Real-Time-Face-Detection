# Real-Time-Face-Detection
Beginner-level real-time face detection using Python and OpenCV
📸 Real-Time Face Detection Using OpenCV (Python)

📌 Project Overview
This project implements a real-time face detection system using a webcam and OpenCV’s Haar Cascade classifier. It detects human faces live from video input, draws bounding boxes around detected faces, and provides an interactive interface with both keyboard and mouse-based exit controls.
The application demonstrates practical use of computer vision techniques for real-time object detection.

❓ Problem Statement
Manual identification of faces in live video streams is inefficient and impractical for real-time applications.
The objective of this project is to automatically detect human faces in real time using a webcam, leveraging classical computer vision techniques.

⚙️ Approach & Methodology
Webcam Access
  Captured live video stream using OpenCV
Image Preprocessing
  Converted frames to grayscale for efficient processing
Face Detection
  Used Haar Cascade classifier (haarcascade_frontalface_default.xml)
  Detected faces using sliding window technique
Visualization
  Drew bounding boxes around detected faces
  Displayed detection results in real time
User Interaction
  Press q to quit
Click on a custom CLOSE button rendered on the video frame

🧠 Technologies Used
Python
OpenCV (cv2)
Haar Cascade Classifier
Webcam (Real-Time Video Capture)

