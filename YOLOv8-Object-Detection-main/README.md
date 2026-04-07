# YOLOv8 Object Detection System

## Project Overview
This project implements an object detection system using the YOLOv8 deep learning model. The goal of the project is to design and optimize a pipeline capable of detecting multiple objects such as persons, vehicles, and traffic signs in images.

The project demonstrates the complete workflow of object detection including dataset preparation, model training, evaluation, and inference.

## Technologies Used
- Python
- Ultralytics YOLOv8
- PyTorch
- Google Colab
- OpenCV
- Matplotlib

## Dataset
The dataset used for training is **COCO128**, a subset of the COCO dataset containing 128 annotated images across multiple object categories.

Dataset Source:
https://github.com/ultralytics/yolov5/releases/download/v1.0/coco128.zip

## Model
The model used in this project is **YOLOv8n (Nano)** which is a lightweight version of YOLOv8 designed for fast training and inference.

## Training Details
- Image size: 640
- Epochs: 40
- Batch size: 16
- Hardware: Google Colab GPU (Tesla T4)

## Performance Metrics
The trained model was evaluated using standard object detection metrics.

Approximate results:

- Precision: 0.017
- Recall: 0.446
- mAP50: 0.34
- mAP50-95: 0.28

## Results
The system successfully detected multiple objects including:

- Person
- Bus
- Stop Sign
- Vehicles

Example detection output:

(Insert detection image here)

## Repository Structure
