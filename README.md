# <div align="center">Detect and recognize license plates</div>

This project aims to detect and recognize vehicle license plates using YOLOv8 for detection and OCR models like Keras OCR and EasyOCR for recognition. The dataset is sourced from Roboflow, and the model is trained over 30 epochs with an image size of 640 and batch size of 32.

## Project Overview

The primary goal is to create a robust pipeline for detecting and extracting text from license plates in real-time. The following tools are utilized:

YOLOv8: For detecting the bounding boxes of license plates.
Keras OCR and EasyOCR: For optical character recognition to read the detected license plates.

## Features

- Detects vehicle license plates from images or videos.
- Recognizes and extracts the characters from the plates using OCR techniques.
- Highly customizable and scalable for different regions and license plate formats.

## Model Details

- Dataset: Obtained from Roboflow.
- Epochs: 30
- Image Size: 640x640
- Batch Size: 32
- Frameworks: YOLOv8 for detection, Keras OCR, and EasyOCR for recognition.
