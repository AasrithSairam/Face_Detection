# Face_Detection

# Face Detection using OpenCV

This project demonstrates real-time face detection using OpenCV and a webcam. By leveraging a pre-trained Haar Cascade Classifier, the application detects faces in video frames captured from your webcam and displays the results in real-time.

## Overview

Face detection is a computer vision task that involves identifying and locating human faces in images or videos. In this project, OpenCV is used to implement face detection using Haar Cascade Classifiers, which are widely used for real-time face detection applications.

This program captures live video from a webcam, converts each frame to grayscale (for performance optimization), and processes the frame to detect faces. When a face is detected, the program draws a green rectangle around the face in the frame. The user can exit the program at any time by pressing the 'q' key.

## Features

- Real-time face detection from a webcam feed
- Detection of multiple faces in the same frame
- Simple and easy-to-understand Python code
- Uses OpenCV, a popular library for computer vision tasks

## Requirements

To run this project, you'll need:

- **Python 3.x** or higher
- **OpenCV** library, which can be installed via `pip`

### Install Dependencies

Before running the code, make sure you have the required Python libraries installed. You can install them using the following command:

```bash
pip install opencv-python

