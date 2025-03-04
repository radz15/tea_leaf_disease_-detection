# tea_leaf_disease_detection
## Overview

Tea leaf diseases can significantly impact crop quality and yield. This project presents a deep learning-based approach using a Convolutional Neural Network (CNN) to accurately classify tea leaf diseases. The model is trained on a dataset containing images of eight classes, including healthy and diseased leaves. The goal is to provide an automated system for early disease detection to aid farmers and agricultural researchers.

## Features
1- Image Preprocessing:  Resizing, rescaling, and data augmentation for enhanced model performance.

2- CNN-Based Model: A deep learning architecture for feature extraction and classification.

3- Performance Evaluation:  Confusion matrix, classification report, and accuracy plots for validation.

4- Model Checkpointing: Saves the best model based on validation loss.

5- Future Enhancements: Integration with IoT-based monitoring and edge computing for real-time detection.

6- Dataset:
The dataset consists of images categorized into eight classes:
- Healthy Leaves
- Anthracnose
- Red Leaf Spot
- White Spot
- Brown Blight
- Bird Eye Spot
- Grey Light
- Algal Leaf
  
7- Images are stored in labeled folders, and the dataset is split into 70% training, 15% validation, and 15% testing.

## Model Architecture
The CNN model follows this architecture:

- Convolutional Layers – Extract features from images.
- MaxPooling Layers – Reduce feature map size while retaining key information.
- Flatten Layer – Converts extracted features into a vector.
- Fully Connected (Dense) Layers – Classifies diseases.
- Softmax Output Layer – Predicts the probability of each class.

  
## Performance Metrics
- Confusion Matrix – Evaluates per-class accuracy.
- Classification Report – Shows precision, recall, and F1-score.
- Training & Validation Accuracy Graphs – Monitors model performance.

