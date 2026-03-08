# Smartvision---Object-Detection-and-Autonomous-vehicle-control

## Overview
SmartVision is a computer vision-based traffic monitoring system that detects and tracks vehicles using object detection models. Development of a real-time object recognition pipeline using Python, YOLOv10, NLP, and OpenCV, integrated into the CARLA simulator. This enables vehicles with autonomous driving functions by working on time series of sensor data to detect obstacles and lane markings, ensuring safe driving. The system analyzes traffic flow from video footage and provides real-time detection of vehicles and traffic signs.

This project demonstrates the use of deep learning and computer vision techniques for intelligent transportation systems.

---

## Simulation Environment

This project was tested using the **CARLA Autonomous Driving Simulator** for virtual vehicle testing.

The system processes live sensor data to detect nearby obstacles and automatically stop the vehicle to prevent collisions.

Note:
Due to the large size of the CARLA simulator and related dependencies, the full simulation environment is not included in this repository.

---

## CARLA Simulation Integration

This project was originally integrated with the CARLA Autonomous Driving Simulator for virtual testing of autonomous vehicle behavior.

The object detection system was used to detect obstacles, vehicles, and traffic signs from the simulated camera feed. Sensor data from the simulation environment was used to estimate object proximity and automatically trigger braking to prevent collisions.

Note:
Due to the large size and environment dependencies of the CARLA simulator setup, the simulation integration scripts are not included in this repository.

This repository currently includes the object detection pipeline and testing code used for vehicle and traffic object detection.

---

Evaluation Metrics
mAP@50: ~0.80 
Precision: ~0.85
Recall: ~0.78

---

## Features

- Real-time vehicle detection
- Traffic flow monitoring
- Object detection using YOLO models
- Vehicle tracking from video streams
- Detection of traffic signs
- Visualization of detected objects

---

## Technologies Used

- Python
- OpenCV
- YOLO (v8 / v10)
- PyTorch
- NumPy
- Jupyter Notebook

---
