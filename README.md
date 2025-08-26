# 🐱 vs 🐶 Image Classification using Deep Learning

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0-FF6F00?style=for-the-badge&logo=tensorflow)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab)

A convolutional neural network (CNN) that classifies images of cats and dogs with **over 85% accuracy** using TensorFlow 2.0 and Keras.

##  Overview

This project implements a deep learning solution for binary image classification, distinguishing between cats and dogs using a custom Convolutional Neural Network architecture. The model achieves **85%+ validation accuracy** through strategic data augmentation and optimized network design.

##  Key Features

- **Deep Learning Pipeline**: End-to-end image classification workflow
- **Data Augmentation**: Enhanced training with random transformations
- **CNN Architecture**: Custom 4-layer convolutional network with dropout
- **Visual Analytics**: Real-time training progress and accuracy graphs
- **High Performance**: 85%+ accuracy on validation dataset

##  Results

| Metric | Performance |
|--------|-------------|
| **Validation Accuracy** | 85%+ |
| **Training Accuracy** | 92%+ |
| **Model Parameters** | ~3.5M |
| **Training Time** | ~5-10 minutes |

##  Tech Stack

- **Framework**: TensorFlow 2.0, Keras
- **Language**: Python 3.8+
- **Environment**: Google Colab
- **Libraries**: NumPy, Matplotlib, ImageDataGenerator

##  Model Architecture
Input (150x150x3)
  ↓
Conv2D (32 filters) + ReLU → MaxPooling2D
  ↓
Conv2D (64 filters) + ReLU → MaxPooling2D
  ↓
Conv2D (128 filters) + ReLU → MaxPooling2D
  ↓
Conv2D (128 filters) + ReLU → MaxPooling2D
  ↓
Flatten → Dropout (0.5)
  ↓
Dense (512 units) + ReLU
  ↓
Output (1 unit) + Sigmoid


##  Quick Start

### Prerequisites
- Google Colab account
- Basic Python knowledge

### Running in Google Colab
1. **Open the Notebook**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/srizoni-maity/Cats-vs-Dogs-Image-Classifier/blob/main/model.ipynb)
2. **Run all cells**: Execute the entire notebook sequentially
3. **View results**: Watch real-time training and accuracy graphs

##  Performance

![Training Progress](https://github.com/srizoni-maity/Cats-vs-Dogs-Image-Classifier/blob/main/graph.jpeg)

##  Skills Demonstrated

- **Deep Learning**: CNN architecture design and implementation
- **Computer Vision**: Image preprocessing and augmentation
- **Data Science**: Model training, validation, and evaluation
- **MLOps**: End-to-end machine learning pipeline development
- **Visualization**: Training progress and result analysis

##  Author

**Srizoni Maity**  
- GitHub: [@srizoni-maity](https://github.com/srizoni-maity)
- LinkedIn: [https://www.linkedin.com/in/srizoni-maity-012235356]

##  Acknowledgments
Dataset provided by Google ML Education
- TensorFlow and Keras documentation
- Google Colab for cloud computing resources


