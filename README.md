OpenCV Face Detection

A simple real-time face detection project built using Python and OpenCV. The project captures video from the webcam and detects faces using the Haar Cascade Classifier, highlighting detected faces with bounding boxes.

Features

- Real-time webcam video capture
- Face detection using Haar Cascade Classifier
- Converts video frames to grayscale for detection
- Draws bounding boxes around detected faces
- Displays a "Face" label on detected faces
- Press "ESC" to exit the application

Technologies Used

- Python
- OpenCV
- Haar Cascade Classifier

Requirements

Install OpenCV using:

pip install opencv-python

Project Structure

opencv-face-detection/
│
├── face_detection.py
├── haarcascade_frontalface_default.xml
└── README.md

How to Run

1. Clone the repository.
2. Make sure your webcam is connected.
3. Install the required package:

pip install opencv-python

4. Run the Python file:

python face_detection.py

5. The webcam will open and detected faces will be highlighted with a red rectangle.
6. Press "ESC" to close the application.

How It Works

The webcam captures video frames using OpenCV. Each frame is converted from BGR to grayscale, and the Haar Cascade Classifier searches for facial features. When a face is detected, the program draws a bounding box around it and displays the "Face" label.

Future Improvements

- Improve detection accuracy
- Add eye detection
- Add face recognition
- Save detected face images
- Add support for multiple cameras
- Explore deep-learning-based face detection
