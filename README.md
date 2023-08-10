# Plant-Disease-Detection
# Plant Disease Detection using Faster R-CNN-MobileNetV2



## Overview

This repository contains the implementation of a deep learning-based object detection framework for plant disease detection in smart agriculture. The framework utilizes the Faster R-CNN architecture with a MobileNetV2 backbone for efficient and accurate disease classification and localization.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Training](#training)
  - [Inference](#inference)
- [Results](#results)
  - [Model Performance](#model-performance)
  - [Sample Images](#sample-images)
- [References](#references)

## Getting Started

### Prerequisites

- Python 3.7+
- TensorFlow 2.x
- Keras
- ...

### Installation

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.

## Usage

### Training

1. Organize your dataset into the appropriate directory structure (refer to the documentation).
2. Set the paths to your training and validation datasets in the code.
3. Customize hyperparameters, such as batch size, learning rate, and number of epochs, as needed.
4. Run the training script: `python train.py`.

### Inference

1. Load the trained model using `loaded_model = load_model("path/to/model.h5")`.
2. Use the `predict_disease(image_path)` function to make predictions on new images.

## Results

### Model Performance

- Training and validation accuracy/loss curves.
- Confusion matrix or classification report.

### Sample Images

- Showcase sample images with bounding boxes drawn around detected diseases.

## References

1. Kaggle. Plant Village Dataset. [Link](https://www.kaggle.com/emmarex/plantdisease)
2. TensorFlow. MobileNetV2. [Link](https://www.tensorflow.org/api_docs/python/tf/keras/applications/MobileNetV2)


Feel free to customize this README file to suit your project's specific details and requirements. Make sure to provide clear instructions and explanations to help users understand and use your project effectively.
