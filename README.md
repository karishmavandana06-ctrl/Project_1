# Project Title/Enhanced Real Time-Drone Detection using Yolo

## Over view
The Drone Detection Using YOLOv5 project is an advanced computer vision application designed to detect and classify drones in real-time. The system uses deep learning techniques to identify drones from images and live video streams while differentiating them from birds and other aerial objects. This project aims to improve surveillance and security systems by providing accurate, fast, and reliable drone detection capabilities in various environmental conditions.

## Objectives
To develop an intelligent drone detection system using deep learning.
To accurately distinguish drones from birds and similar flying objects.
To achieve real-time object detection with high speed and accuracy.
To reduce false alarms in surveillance applications.
To improve security monitoring in sensitive and restricted areas.

## Features
Real-time drone detection from images and videos.
Drone and bird classification.
High-speed object detection using YOLOv5.
Bounding box generation around detected objects.
Confidence score display for each prediction.
Support for surveillance and security monitoring applications.
Ability to work under different lighting and background conditions.
Accurate detection of small drones at varying distances.

## Technologies Used
Python
YOLOv5
PyTorch
OpenCV
NumPy
Google Colab
Roboflow

## Dataset Description
The project utilizes a mixed dataset containing drone and bird images collected from multiple sources. The dataset includes aerial objects captured under different environmental conditions, lighting variations, object sizes, and backgrounds. Data augmentation techniques such as image rotation, horizontal flipping, scaling, and brightness adjustment were applied to increase dataset diversity and improve model generalization. Proper annotation was performed using bounding boxes to accurately identify object locations.

## System Architecture
The system follows a structured workflow consisting of multiple stages:
Data Collection
Image Annotation
Dataset Preparation
Image Preprocessing
Feature Extraction
YOLOv5 Model Training
Object Detection
Classification
Output Visualization
Performance Evaluation
The architecture ensures accurate object localization, classification, and real-time monitoring.

## Image Preprocessing
Before training the model, several preprocessing techniques were applied to improve data quality:
Image resizing to 640×640 resolution.
Pixel value normalization.
Data augmentation.
Brightness and contrast enhancement.
Horizontal flipping.
Rotation and scaling transformations.
These preprocessing techniques help improve model robustness and detection performance.

## YOLOv5 Model
YOLOv5 is a state-of-the-art object detection model known for its speed and accuracy. It processes the entire image in a single forward pass, making it highly suitable for real-time applications. The model consists of:
Backbone Network
Neck Network
Detection Head
YOLOv5 was selected after comparing its performance with other YOLO variants due to its better balance between detection accuracy and inference speed.

## Performance Evaluation
The system performance was evaluated using standard object detection metrics:
Precision
Measures the accuracy of detected objects.
Recall
Measures the model's ability to detect all relevant objects.
F1-Score
Provides a balanced evaluation of precision and recall.
Mean Average Precision (mAP)
Measures overall detection accuracy and localization performance.
Detection Speed
Evaluates the number of frames processed per second (FPS) for real-time detection.

##Results
The proposed YOLOv5-based drone detection system achieved:
High drone detection accuracy.
Faster real-time processing.
Improved drone and bird classification.
Reduced false positive detections.
Better performance under complex environmental conditions.

## Advantages
High accuracy object detection.
Real-time monitoring capability.
Reduced false alarms.
Fast processing speed.
Effective small object detection.
Cost-effective implementation.
Easy deployment on surveillance systems.
Scalable architecture for future improvements.


## Applications
Airport Security.
Border Surveillance.
Military Monitoring.
Restricted Area Protection.
Smart City Surveillance.
Critical Infrastructure Monitoring.
Industrial Security Systems.


## Future Enhancements
Integration with CCTV cameras.
Mobile application support.
Multi-drone detection.
Alert notification system.
Cloud-based monitoring dashboard.
Automatic threat analysis and reporting.
Integration with IoT-based surveillance systems.


## License
This project is for educational and research purposes.
