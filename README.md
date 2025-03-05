# Object detection using Yolo in Image, video, and webcam.

This project implements object detection in various scenarios, including static images, video files, and real-time webcam feeds. It utilizes machine learning models, likely based on YOLO (You Only Look Once) or OpenCV, to identify and track objects within different media formats.

Features
1. Object Detection in Images (object detection in an image.py):
Detects objects in a given static image and annotates them with bounding boxes.

2. Object Detection in Video (object detection using video.py):
Processes a video file to identify objects frame by frame and overlays bounding boxes.

3. Real-Time Object Detection (Real time object detection.py):
Utilizes a webcam feed to detect objects in real time and visualize detections on-screen.

Dependencies
Ensure you have the following dependencies installed before running the scripts:

pip install opencv-python numpy ultralytics torch torchvision

Usage :
Object Detection in an Image
python object\ detection\ in\ an\ image.py --image <path_to_image>

Object Detection in a Video:
python object\ detection\ using\ video.py --video <path_to_video>

Real-Time Object Detection:
python Real\ time\ object\ detection.py

Input Files:
r1234.jpg & r12345.jpeg: Sample images for testing image-based object detection.
test.mp4: Sample video for evaluating video-based object detection.

Even custom datasets can be given but note to change the address of the locations accordingly

Future Improvements
1. Enhance model accuracy with better pre-trained weights.
2. Implement tracking for more stable detections.
3. Optimize performance for real-time detection with efficient inference techniques.

project refered & creds goes to Shantam Sultania !!
To learning !!!

