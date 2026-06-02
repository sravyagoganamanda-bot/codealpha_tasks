# Handwritten Character Recognition using CNN

## Overview
This project implements a Handwritten Character Recognition system using a Convolutional Neural Network (CNN) and the MNIST dataset. The model is trained to recognize handwritten digits from 0 to 9 with high accuracy.

## Objective
To identify handwritten digits using image processing and deep learning techniques.

## Dataset
MNIST Dataset

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Model Architecture
- Conv2D Layer (32 filters)
- MaxPooling2D
- Conv2D Layer (64 filters)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 neurons)
- Output Layer (10 classes)

## Results
- Training Accuracy: 99.44%
- Validation Accuracy: 98.88%

## Features
- Image preprocessing
- CNN-based classification
- Model evaluation
- Handwritten digit prediction
- Trained model saved as .h5 file

## Project Structure

CodeAlpha_HandwrittenCharacterRecognition/
│
├── handwritten_character_recognition.ipynb
├── digit_model.h5
├── requirements.txt
├── README.md
└── screenshots/

## Future Improvements
- Character recognition using EMNIST
- Alphabet recognition
- Word and sentence recognition using CRNN models

## Author
Sravya Goganamanda
