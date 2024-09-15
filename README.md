# Automatic Number Plate Recognition (ANPR)

## Project Overview
This project implements **Automatic Number Plate Recognition (ANPR)** using the **YOLOv8 (You Only Look Once)** object detection algorithm.

It detects vehicle license plates and uses Optical Character Recognition (OCR) to extract and recognize the characters on the plates.

## Key Features
- Real-time detection of number plates from images or video feeds.
- Character recognition using EasyOCR for accurate text extraction.
- Utilizes YOLOv8 for efficient and accurate number plate detection.
- Handles a variety of vehicle plate styles and lighting conditions.

## Libraries and Dependencies
- **Ultralytics YOLOv8 (v8.0.114)**: For object detection and localization of number plates.
- **pandas (v2.0.2)**: Data manipulation and handling for processing results.
- **OpenCV (v4.7.0.72)**: Image and video processing for detecting number plates.
- **numpy (v1.24.3)**: Numerical operations and array handling for image data.
- **scipy (v1.10.1)**: Used for advanced image processing and mathematical operations.
- **EasyOCR (v1.7.0)**: Optical Character Recognition to extract text from the detected plates.
- **FilterPy (v1.4.5)**: For tracking and filtering data to improve detection accuracy.
