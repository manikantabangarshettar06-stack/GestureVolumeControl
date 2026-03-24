**Overview**

The Gesture-Based Volume Control System is a computer vision-based project that allows users to control system volume using hand gestures. Instead of using a mouse or keyboard, the system uses a webcam to detect hand movements and converts them into volume control commands in real time.

This project is an example of Human-Computer Interaction (HCI), where natural gestures are used to interact with digital systems. By measuring the distance between the thumb and index finger, the system adjusts the volume smoothly and efficiently.

**Features**

1. Real-time hand tracking using webcam
2. Gesture-based volume control
3. Smooth and continuous volume adjustment
4. Noise reduction using filtering techniques
5. Simple and intuitive interaction
6. Fast response with low latency

**Technologies Used**

1. Python
2. OpenCV
3. MediaPipe
4. NumPy
5. PyCaw / Pygame
6. Basic Signal Processing (FFT)

**How It Works**

1. The webcam captures video frames continuously.
2. MediaPipe detects the hand and identifies 21 landmarks.
3. The positions of the thumb and index finger are extracted.
4. The distance between these fingers is calculated.
5. This distance is mapped to a volume range (0%–100%).
6. Filtering is applied to reduce noise.
7. The system volume is adjusted accordingly.

**Installation**

*Prerequisites*

1. Python 3.7 or above
2. pip installed

*Install Required Libraries*

Run the following command:
pip install opencv-python mediapipe numpy pycaw pygame

**System Requirements**

1. Webcam
2. Moderate system performance
3. Good lighting conditions

**Results**

The system successfully detects hand gestures and controls volume in real time. It provides smooth and responsive output with minimal delay. Under proper lighting conditions, the accuracy is high and user experience is good.

**Limitations**

1. Depends on lighting conditions
2. Less accurate with fast hand movements
3. Requires hand to stay within camera frame
4. Affected by background clutter
5. Small hand movements may cause fluctuations

**Applications**

1. Touchless control systems
2. Assistive technologies
3. Smart devices
4. Gaming and AR/VR systems

**Project Structure**

gesture-volume-control

│── main.py

│── requirements.txt

│── README.md

│── assets

│── utils

**Acknowledgements**

1. MediaPipe
2. OpenCV
3. Python community

**License**

This project is open-source under the MIT License.

*Demo*

https://drive.google.com/file/d/16IQjZlTa0QoHIeuBpR2PMWQnx5bpuTLS/view?usp=sharing
