# Pizza or Not Pizza

## Overview

This repository contains the code for building a Convolutional Neural Network (CNN) for binary classification: determining whether an image contains a pizza or not. The model is trained on the "Pizza or not Pizza?" dataset available on Kaggle.

## Dataset

The "Pizza or not Pizza?" dataset is available on Kaggle: [Pizza or not Pizza? Dataset](https://www.kaggle.com/example/pizza-or-not-pizza).

- **Dataset Description:** The dataset consists of images containing pizzas and non-pizza objects. The binary classification task is to classify whether an image contains a pizza or not.

- **Dataset Structure:**
  - `train/`: Training images
  - `test/`: Test images
  - `labels.csv`: CSV file containing image filenames and corresponding labels (1 for pizza, 0 for not pizza)


## Model Architecture

The CNN model is designed to analyze images and classify them as either Pizza or Not Pizza cases. It consists of convolutional layers, pooling layers, and fully connected layers. You can modify the architecture based on your experimentation.

## Results
The model achieves an accuracy of 87% on the test set. For detailed performance metrics, refer to the Notebook.

## View On Kaggle
You can also check out this Notebook on Kaggle using following link:
https://www.kaggle.com/code/sharduljoshi29/pizza-or-not-pizza-using-cnn
