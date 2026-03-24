**Overview**

The Gesture-Based Volume Control System is a computer vision-based project that allows users to control system volume using hand gestures. Instead of using a mouse or keyboard, the system uses a webcam to detect hand movements and converts them into volume control commands in real time.

This project is an example of Human-Computer Interaction (HCI), where natural gestures are used to interact with digital systems. By measuring the distance between the thumb and index finger, the system adjusts the volume smoothly and efficiently.

**Features**

i.Real-time hand tracking using webcam
ii.Gesture-based volume control
iii.Smooth and continuous volume adjustment
iv.Noise reduction using filtering techniques
v.Simple and intuitive interaction
vi.Fast response with low latency

**Technologies Used**

i.Python
ii.OpenCV
iii.MediaPipe
iv.NumPy
v.PyCaw / Pygame
vi.Basic Signal Processing (FFT)

**How It Works**

1.The webcam captures video frames continuously.
2.MediaPipe detects the hand and identifies 21 landmarks.
3.The positions of the thumb and index finger are extracted.
4.The distance between these fingers is calculated.
5.This distance is mapped to a volume range (0%–100%).
6.Filtering is applied to reduce noise.
7.The system volume is adjusted accordingly.

**Installation**

**Prerequisites*

i.Python 3.7 or above
ii.pip installed

**Install Required Libraries*

Run the following command:
pip install opencv-python mediapipe numpy pycaw pygame

**System Requirements**

i.Webcam
ii.Moderate system performance
iii.Good lighting conditions

**Results**

The system successfully detects hand gestures and controls volume in real time. It provides smooth and responsive output with minimal delay. Under proper lighting conditions, the accuracy is high and user experience is good.

**Limitations**

i.Depends on lighting conditions
ii.Less accurate with fast hand movements
iii.Requires hand to stay within camera frame
iv.Affected by background clutter
v.Small hand movements may cause fluctuations

**Applications**

i.Touchless control systems
ii.Assistive technologies
iii.Smart devices
iv.Gaming and AR/VR systems

**Project Structure**

gesture-volume-control/
│── main.py
│── requirements.txt
│── README.md
│── assets/
│── utils/

**Acknowledgements**

i.MediaPipe
ii.OpenCV
iii.Python community

**License**

This project is open-source under the MIT License.

**Demo*

https://drive.google.com/file/d/16IQjZlTa0QoHIeuBpR2PMWQnx5bpuTLS/view?usp=sharing
