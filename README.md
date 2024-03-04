# MNIST Digit Classifier

This repository contains a machine learning project that aims to classify handwritten digits using the MNIST dataset. The MNIST dataset is a large database of handwritten digits commonly used for training and testing in the field of machine learning.

## Project Overview

The project uses a Convolutional Neural Network (CNN) implemented with TensorFlow and Keras. The model is trained to recognize digits from 0 to 9 with high accuracy.

## Features

- Data preprocessing and augmentation to improve model robustness.
- CNN with multiple layers for feature extraction and classification.
- Evaluation scripts to assess model accuracy and performance.

## Requirements

jupyter
ipykernel
numpy
pandas
tensorflow
scikit-learn
matplotlib
seaborn
idx2numpy
optuna
opencv-python
pyheif
pillow-heif

## Usage

create a virutal env
```bash
pip install -r requirements.txt
notebook
```

## Model Performance

This model is performing with a 98.9% accuracy. However, when testing with external data that is not pre-processed the same exact way, its performance is not fantastic (not enough tests run to generate an accuracy score). With additional time, I would attempt to make the model more versatile or automate the preprocessing completely.
