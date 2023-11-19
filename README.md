# Pneumonia-detection-based-on-X-ray-images

## Overview
This repository contains a machine learning project aimed at detecting pneumonia from chest X-ray images using convolutional neural networks (CNNs). The project leverages TensorFlow and Keras for building and training models, including a custom CNN architecture and a fine-tuned pre-trained ResNet152V2 model. The dataset used comprises chest X-ray images labeled as 'Normal' and 'Pneumonia', and the models are trained, evaluated, and fine-tuned to achieve high accuracy in classifying these images. This work exemplifies the application of deep learning in medical imaging, contributing to the field of automated diagnostic tools.

## Models
- Custom CNN Model
- Pre-trained ResNet152V2 with Fine-tuning

## Data
The dataset consists of chest X-ray images categorized into 'Normal' and 'Pneumonia'. Images are split into training, validation, and test sets.
Dataset Source: [Chest X-Ray (Pneumonia) with CNN] https://www.kaggle.com/code/hossamgalal68/chest-x-ray-pneumonia-with-cnn/data

### Prerequisites
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- Plotly
- Seaborn
- Scikit-learn
- Pandas
- NumPy

## Results
The models' performance can be observed in the Jupyter notebooks provided. The fine-tuned ResNet152V2 model achieved the highest accuracy.
