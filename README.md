Real-Time Hand and Finger Tracking using MediaPipe + OpenCV

Description:
This project uses computer vision to detect and track human hands in real-time using a webcam. It identifies key hand landmarks (fingertips and joints) and visualizes them on the screen.

The system is built using Python, OpenCV, and Google's MediaPipe library.

Features:
- Real-time hand detection using webcam
- Tracks up to 4 hands simultaneously
- Identifies key fingertip landmarks (thumb, index, middle, ring, pinky)
- Draws hand skeleton and labels fingertips
- Displays live video feed with overlays

Technologies Used:
- Python
- OpenCV
- MediaPipe
- Time module

How it works:
1. Captures video from webcam
2. Converts frame to RGB
3. Processes frame using MediaPipe Hands solution
4. Extracts 21 hand landmarks per detected hand
5. Identifies fingertip points
6. Draws landmarks and labels on the frame

Controls:
- Press 'q' to exit the program

Requirements:
pip install opencv-python mediapipe

How to Run:
python main.py

Future Improvements:
- Gesture recognition (like open/close fist)
- Mouse control using hand movement
- Virtual keyboard using gestures
- Multi-hand gesture actions

Author:
Burhan Ahmed.
