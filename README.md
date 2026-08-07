# Pepper Leaf Disease Detection Using Transfer Learning and XAI

## Overview
Automated detection of Bacterial Spot disease in pepper leaves using Transfer Learning and Grad-CAM explainability.

## Models Used
- MobileNetV2 — 92.40% accuracy
- VGG16 — 95.00% accuracy (Best Model)
- ResNet50 — 66.43% accuracy

## Dataset
PlantVillage Dataset — 1,915 pepper leaf images
- Bacterial Spot: 997 images
- Healthy: 918 images

## Results
| Model | Accuracy |
|---|---|
| MobileNetV2 | 92.40% |
| VGG16 | 95.00% |
| ResNet50 | 66.43% |

## Features
- Transfer Learning with ImageNet weights
- Grad-CAM XAI visualization
- Confusion Matrix analysis
- Classification Report

## Tech Stack
Python, TensorFlow, Keras, Google Colab, NVIDIA T4 GPU

## How to Run
1. Open the `.ipynb` file in Google Colab
2. Mount Google Drive
3. Run all cells in order
