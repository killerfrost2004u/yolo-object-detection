# Object Detection with YOLO on Glasses Detection Dataset

## Overview
This Jupyter Notebook demonstrates the process of setting up an object detection project using the YOLO (You Only Look Once) model. The dataset used is the "Glasses Detection YOLO Format" from Kaggle, which contains images and corresponding label files in YOLO format.

## Requirements
To run this notebook, the following libraries are required:

- `ultralytics` (for YOLO model)
- `kagglehub` (to download the dataset)
- `roboflow` (for data handling)
- `split-folders` (for dataset splitting)
- `opencv-python` (for image processing)
- `matplotlib` (for visualization)
- `torch` (PyTorch for deep learning)
- `scikit-learn` (for train-test split)
- `numpy`, `PIL`, `yaml`, `os`, `shutil`, etc.

Install the required packages using:
```bash
pip install ultralytics kagglehub roboflow split-folders opencv-python matplotlib torch scikit-learn
