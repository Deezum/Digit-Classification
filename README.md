# Binary Digit Classifier

This repository contains a neural network classifier that is designed to classify images of handwritten binary digits (0 or 1) from the MNIST dataset. The project was built using TensorFlow and Keras.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [License](#license)

## Project Overview

The goal of this project is to create a neural network that can accurately classify handwritten binary digits (0 and 1). The MNIST dataset is used, but only the digits labeled '0' or '1' are extracted for this binary classification task.

## Dataset

The MNIST dataset is a large collection of handwritten digits. We are specifically using:
- Training set: 12,665 images labeled as either '0' or '1'.
- Test set: A smaller subset for evaluation.

The dataset is loaded using TensorFlow's `keras.datasets.mnist` module, and the digits are filtered to keep only '0's and '1's.

## Model Architecture

The neural network is built using TensorFlow and Keras. Key steps in the project include:
- Data Preprocessing: Filtering the dataset to include only the binary digits.
- Model Design: A simple neural network with layers suitable for image classification.
- Training: The model is trained on the filtered dataset of binary digits.
- Evaluation: The model is evaluated on the test set to check accuracy and performance.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- TensorFlow
- NumPy

You can install the dependencies using pip:

```bash
pip install tensorflow numpy

