# Potato_Disease_Classification
# 🧠 CNN Image Classification with TensorFlow

This project builds and trains a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify images into 3 different categories.

## 🚀 Features

- TensorFlow/Keras-based CNN model
- Automatic image resizing, rescaling, and data augmentation
- Data partitioning: Train / Validation / Test sets
- Multiple convolutional layers for deep feature extraction
- Final softmax classifier for multi-class prediction
- Visualization of accuracy and loss over epochs

## 🖼️ Sample Model Architecture

```plaintext
Input (Resized & Rescaled)
↓
Data Augmentation (RandomFlip, RandomRotation)
↓
Conv2D → MaxPooling2D (x6 times)
↓
Flatten
↓
Dense Layer
↓
Softmax Output (3 classes)
