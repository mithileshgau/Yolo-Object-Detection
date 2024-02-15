# Yolo-Object-Detection
yolov8 object detection on liver disease dataset

## Overview
Object detection algorithms have the potential to revolutionize medical diagnostics, and this project focuses on automating the detection and classification of liver disease in medical images. By leveraging the power of YOLO (You Only Look Once) models, specifically YOLOv8, we aim to contribute to the advancement of object detection techniques in the medical domain.

## Motivation
Accurate identification of liver disease through automated algorithms can significantly improve patient outcomes and treatment success rates. This project seeks to develop a system that assists medical professionals in diagnosing liver diseases, leading to faster and more accurate diagnoses.

## YOLO Framework
Renowned for its real-time capabilities, YOLO models, including YOLOv8 and YOLOv7, adopt a single-shot detection approach. By processing the entire image in a single pass, these models predict bounding box coordinates and class probabilities, making them particularly suitable for real-time applications.

## Dataset

![alt text](https://github.com/mithileshgau/Yolo-Object-Detection/blob/dev/Images/Dataset.png)
In the context of medical imaging, liver disease detection and classification present unique challenges. We utilized a carefully annotated liver disease dataset as part of the Roboflow initiative. This dataset comprises 3976 data points covering classes such as ballooning, fibrosis, inflammation, and steatosis. See Figure 1 for a snippet of the dataset.



## Metrics

![alt text](https://github.com/mithileshgau/Yolo-Object-Detection/blob/dev/Images/YoloV8%20Metrics.png)
The evaluation metrics for the YOLOv8 model on the liver disease dataset are as follows:

mAP@50: 58.5%
Precision: 57.6%
Recall: 58.4%
These metrics showcase the model's performance in terms of accuracy, precision, and recall in detecting and classifying liver diseases.

## Evaluation Examples

![alt text](https://github.com/mithileshgau/Yolo-Object-Detection/blob/dev/Images/Prediction%201.png)

![alt text](https://github.com/mithileshgau/Yolo-Object-Detection/blob/dev/Images/Prediction%202.png)

![alt text](https://github.com/mithileshgau/Yolo-Object-Detection/blob/dev/Images/Prediction%203.png)
