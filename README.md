# Brain Tumor Classification and Detection

A Deep Learning and Computer Vision project for classifying brain images into **Tumor** and **No Tumor** categories and performing real-time detection using **YOLO** and **OpenCV**.

## Project Overview

This project combines a **CNN-based image classification model** with **YOLO object detection** to identify brain tumors from images and video input.

The system can:

* Classify brain images as Tumor or No Tumor
* Detect tumor regions using YOLO
* Display bounding boxes around detected regions
* Display predicted class and confidence score
* Process individual images
* Perform real-time detection on video input

## Technologies Used

* Python
* TensorFlow
* Keras
* Convolutional Neural Networks (CNN)
* YOLO
* OpenCV
* NumPy
* Computer Vision
* Deep Learning

## Features

### Image Classification

The CNN model classifies brain images into:

* Tumor
* No Tumor

### Object Detection

YOLO is used to detect the relevant region in the input image and generate bounding boxes.

### Real-Time Detection

OpenCV is used to process video frames and perform detection and classification in real time.

## Model Components

### CNN Classifier

The CNN-based classifier is trained to distinguish between tumor and non-tumor brain images.

### YOLO Detector

YOLO is used for object detection and localization of the region of interest.

### OpenCV

OpenCV handles image processing, video capture, frame processing, bounding boxes, and displaying prediction results.

## Usage

### Image Prediction

To perform real-time detection using an image for prediction

### Video Prediction

To perform real-time detection using a video

Update the model and input paths in the scripts according to your local setup.

## Example Output

The system displays:

```text
Class: Tumor
Confidence: 0.95
```

For detected regions, bounding boxes are displayed around the predicted area.

## Learning Outcomes

* Deep Learning
* Convolutional Neural Networks
* Image Classification
* Object Detection
* Computer Vision
* YOLO
* OpenCV
* TensorFlow and Keras
* Model Prediction and Evaluation
* Real-Time Video Processing

## Future Improvements

* Improve model accuracy with a larger and more diverse dataset
* Add data augmentation and advanced preprocessing
* Improve tumor localization
* Deploy the model as a web application
* Optimize the model for real-time performance
* Add support for additional tumor categories
