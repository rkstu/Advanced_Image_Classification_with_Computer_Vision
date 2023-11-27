# Project1: Vehicle Identification and Counting with YOLOv8
Explore the comprehensive documentation for a detailed overview and examination of the results: https://drive.google.com/drive/folders/102qL0HvIRccnuTVxKxRN0PC9g73rBe2k?usp=sharing

## Overview
This repository implements the YOLOv8 object detection model with a specific focus on vehicle detection, counting, and speed estimation within both image and video test data. The objective is to provide a comprehensive solution for analyzing traffic scenes, identifying vehicles, counting their numbers, and estimating their speeds.
YOLOv8 Model

The YOLOv8 (You Only Look One-level) model is employed for its robust object detection capabilities. The model divides the input image into a grid and predicts bounding boxes and class probabilities for objects within each grid cell, making it well-suited for detecting and counting multiple objects simultaneously.
Features
- Vehicle Detection and Counting: The model is trained to exclusively identify vehicles within the input frames, providing an accurate count of the number of vehicles present in the scene.
- Speed Estimation: Speed estimation is implemented to calculate the speed of detected vehicles within video frames. This is particularly useful for traffic monitoring and analysis.
- Image and Video Compatibility: The implementation supports both image and video test data, allowing users to analyze individual frames or entire video sequences.

Sample output
![Untitled](https://github.com/rkstu/Computer_vision/assets/93584728/eb9f6f33-8385-4df3-a4ac-f16d0260e37a)


# Project 2 : YOLOv8 Person Detection
Explore the comprehensive documentation for a detailed overview and examination of the results: https://drive.google.com/drive/folders/102qL0HvIRccnuTVxKxRN0PC9g73rBe2k?usp=sharing

## Overview
This repository implements the YOLOv8 object detection model with a specific focus on identifying and locating individuals within images. The primary objective is to exclusively highlight the "person" class in the output, filtering out any other classes that may be present.
YOLOv8 Model

Sample output
![Untitled](https://github.com/rkstu/Computer_vision/assets/93584728/76d5251a-c539-46af-b0b0-75b55443412b)


# Project 3: YOLOv8 Face Detection and Emotion Classification
Explore the comprehensive documentation for a detailed overview and examination of the results: https://drive.google.com/drive/folders/102qL0HvIRccnuTVxKxRN0PC9g73rBe2k?usp=sharing

## Overview
This repository presents a comprehensive solution for face detection and emotion classification using the YOLOv8 object detection model. The pipeline involves training YOLOv8 for face detection, followed by training an image classification model to classify emotions within the detected faces. The emotion categories include 'Happy,' 'Sad,' and 'Neutral,' and the class names are displayed on the face bounding boxes in the output.

## Emotion Classification Model
Once faces are detected, the image classification model is trained to classify emotions into 'Happy,' 'Sad,' and 'Neutral' categories. The training data comprises cropped images from the face detection output.
Features
- Face Detection: YOLOv8 is tailored to excel in face detection, providing precise bounding boxes around detected faces.
- Emotion Classification: The emotion classification model categorizes emotions within the detected faces into 'Happy,' 'Sad,' and 'Neutral' classes.
- Output Visualization: The class names corresponding to the predicted emotions are displayed on the face bounding boxes in the output images.

Sample output:

![image](https://github.com/rkstu/Computer_vision/assets/93584728/2385147f-a731-4611-a009-65f3c98a40ca)
