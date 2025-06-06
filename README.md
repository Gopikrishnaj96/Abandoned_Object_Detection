Abandoned Object Detection


Detects and highlights unattended objects in video streams using background subtraction and temporal tracking.




![Screenshot 2025-06-06 134151](https://github.com/user-attachments/assets/3b8f28c2-b730-461b-9eba-07da93fec2ef)

Features

-Real-time detection of abandoned objects
-Visualizes detection pipeline (edge, diff, and final detection)
-Works with video files or live camera input

Requirements

-Python 3.7+
-opencv-python
-numpy

How It Works

-Captures a reference frame as background.
-Compares each new frame to the reference to spot changes.
-Applies edge detection and morphological operations to isolate objects.
-Tracks objects that remain stationary for a set number of frames.
-Flags and highlights abandoned objects with a bounding box and label.



