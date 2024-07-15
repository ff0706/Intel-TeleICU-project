# Intel-TeleICU-project

Table of Contents:
1. Introduction
2. Features
3. System Architecture
4. Dataset
5. Training the Model
8. Technologies Used
9. Team Members & Contributions

# 1. Introduction
Welcome to the Innovative Monitoring System for TeleICU Patients Using Video Processing and Deep Learning. This project is developed for the Intel Unnati Industrial Training Program 2024. The goal of this project is to reduce the burden on healthcare professionals by enabling them to monitor multiple ICU patients remotely using advanced video processing and deep learning technologies.

# 2. Features
Real-time Video Monitoring: Continuous monitoring of ICU patients through video feeds.

Deep Learning Algorithms: Uses YOLOv8 for precise person classification and MediaPipe for detailed movement classification.

Anomaly Detection: Detects abnormal patient behaviors such as falls, seizures, and breathlessness.

# 3. System Architecture
The system comprises the following components:

Video Capture Module: Captures real-time video streams from ICU rooms.

Preprocessing Module: Processes video frames to prepare them for analysis. 

Deep Learning Model: Analyzes processed video frames to detect anomalies.

# 4. Dataset
We sourced a comprehensive dataset from publicly available YouTube videos relevant to ICU settings. The collected videos were uploaded to Roboflow, annotated with labels (Patient, Nurse, Doctor, Relatives), and used to train the YOLOv8 model.

# 5. Training the Model
Prepare your dataset and ensure it is in the correct format. Then train it on the Yolov8 model and MediaPipe model.

# 6. Technologies Used
Roboflow: For managing and preprocessing image datasets.

YOLOv8: For person classification and fall detection.

MediaPipe: For seizure and breathlessness detection.

OpenCV: For video processing.

Python, PyTorch, TensorFlow: For implementing and training models.

Google Colab: For training and prototyping models.

Hardware: High-resolution cameras and GPUs for model inference.

# 7. Team Members & Contributions
Fathima Fahim [1NT21AD018]: Synopsis, Code, Dataset Creation, Final Report

Manasa S [1NT21AD030]: Synopsis, Code, Dataset Creation, Final Report

Sneha V [1NT21AD052]: Synopsis, Code, Dataset Creation, Final Report
