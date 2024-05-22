## AI-Gym-Poster-Angle

# Description

This repository contains code for detecting and visualizing the angles of movements like curls, sit-ups, squats, etc. using computer vision techniques. The code utilizes the following libraries:
mediapipe for pose estimation
cv2 for image processing
numpy for numerical operations
matplotlib for visualization
Installation
Install the required libraries:
bash
pip install mediapipe opencv-python numpy matplotlib

#Usage
Run the script to detect and visualize movement angles.
Ensure your camera is properly set up to capture the movements.
The script will display the detected angles on the screen.

# Libraries Used
import mediapipe as mp

import cv2

import numpy as np

import matplotlib.pyplot as plt

# Draw landmarks & connections to screen
mp_drawing = mp.solutions.drawing_utils

# Import Pose model
mp_pose = mp.solutions.pose

# Acknowledgements

The pose estimation model is provided by Mediapipe.

OpenCV for image processing capabilities.

Numpy for efficient numerical operations.

Matplotlib for visualizing the detected angles.
