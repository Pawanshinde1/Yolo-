YOLOv8 Object Detection System<br>
Project Overview<br>
This project implements an object detection system using the YOLOv8 deep learning model. The goal of the project is to design and optimize a pipeline capable of detecting multiple objects such as persons, vehicles, and traffic signs in images.<br>

The project demonstrates the complete workflow of object detection including dataset preparation, model training, evaluation, and inference.

Technologies Used<br>
Python<br>
Ultralytics YOLOv8<br>
PyTorch<br>
Google Colab<br>
OpenCV<br>
Matplotlib<br>
Dataset<br>
The dataset used for training is COCO128, a subset of the COCO dataset containing 128 annotated images across multiple object categories.<br>



Model
The model used in this project is YOLOv8n (Nano) which is a lightweight version of YOLOv8 designed for fast training and inference.<br>

Training Details<br>
Image size: 640<br>
Epochs: 40<br>
Batch size: 16<br>
Hardware: Google Colab GPU (Tesla T4)<br>
Performance Metrics<br>
The trained model was evaluated using standard object detection metrics.<br>

Approximate results:<br>

Precision: 0.017<br>
Recall: 0.446<br>
mAP50: 0.34<br>
mAP50-95: 0.28<br>
Results<br>
The system successfully detected multiple objects including:<br>
Person<br>
Bus<br>
Stop Sign<br>
Vehicles<br>
Example detection output:<br>

(Insert detection image here)<br>

Repository Structure
