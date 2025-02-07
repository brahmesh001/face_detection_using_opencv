Real-Time Face Detection using OpenCV

📌 Project Overview

This project implements real-time face detection using OpenCV and Haar Cascade Classifier. The program captures video from the webcam, detects faces frame-by-frame, and highlights them with bounding boxes. The implementation demonstrates fundamental computer vision techniques for object detection in real-time.

🚀 Features

Captures real-time video stream from the webcam.

Converts frames to grayscale for efficient processing.

Detects faces using OpenCV's Haar Cascade Classifier.

Draws bounding boxes around detected faces.

Stops capturing when the user presses the 'q' key.

🛠️ Technologies Used

Python

OpenCV

NumPy

🔧 Installation & Setup

Clone the Repository

git clone https://github.com/yourusername/real-time-face-detection.git
cd real-time-face-detection

Install Dependencies

pip install opencv-python numpy

Download Haar Cascade Classifier

Ensure you have the haarcascade_frontalface_default.xml file in the project directory.

You can download it from OpenCV's GitHub repository.

▶️ Usage

Run the Python script to start real-time face detection:

python face_detection.py

Press 'q' to stop the video stream and close the window.

📜 Code Explanation

Captures video using OpenCV's cv2.VideoCapture(0).

Converts each frame to grayscale (cv2.cvtColor).

Loads the Haar Cascade Classifier.

Detects faces using detectMultiScale() and draws rectangles around them.

Displays the video stream and listens for the 'q' key to exit.


🤝 Contributing

Feel free to open issues or submit pull requests to improve the project!


