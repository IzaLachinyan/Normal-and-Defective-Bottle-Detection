# Normal-and-Defective-Bottle-Detection
# Object Detection Model Training and Inference

## Overview
This repository contains code and instructions for training an object detection model using a dataset of 262 images with 5 classes: "label", "crumbled", "not-crumbled", "cap", and "no-cap". The trained model is then utilized to perform inference on a video to count the number of normal and defective bottles.

## Table of Contents
1. [Dataset Preparation](#dataset-preparation)
2. [Model Training](#model-training)
3. [Inference on Video](#inference-on-video)

## 1. Dataset Preparation<a name="dataset-preparation"></a>
- Ensure that your dataset is organized with labeled images for each class.
- Consider using popular annotation tools like LabelImg or RectLabel to annotate your images.
- Divide the dataset into training and validation sets for model evaluation.

## 2. Model Training<a name="model-training"></a>
### 2.1 Install Required Libraries
```bash
pip install tensorflow opencv-python
