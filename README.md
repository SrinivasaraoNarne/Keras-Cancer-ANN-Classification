# Cancer Classification Using Artificial Neural Networks (ANN)

## Introduction
This repository contains a deep learning project focused on classifying cancer types using Artificial Neural Networks (ANN). Implemented in Python with Keras, the project demonstrates how deep learning techniques can be applied to binary classification tasks in medical diagnostics.

## Overview
Cancer classification plays a vital role in medical diagnostics, aiding in the early detection and treatment of the disease. This project utilizes a dataset containing extracted features from cancer cells to predict whether they are benign or malignant. The model is built using a Sequential ANN architecture in Keras and is trained on labeled medical data to optimize prediction accuracy.

## Features
* Data Preprocessing: Handles missing values, categorical encoding, and feature scaling to enhance model performance.
* ANN Architecture:
  * Input Layer: Processes multiple features from the dataset.
  * Hidden Layers: Fully connected dense layers with ReLU activation for efficient feature extraction.
  * Output Layer: Sigmoid activation for binary classification.
* Performance Metrics: Evaluates model performance using accuracy, precision, recall, F1-score, and confusion matrix.
* Visualization: Provides insights through loss and accuracy plots during training and testing phases.

## Dataset
The dataset used for this project contains features extracted from cancer cell nuclei, such as radius, texture, perimeter, area, and smoothness. It is a clean and labeled dataset suitable for binary classification.
* Source: [Kaggle](https://www.kaggle.com/)
* DATASET: Available above
* DATASET DETAILS: The above dataset contains required data for the project, a dataset of samples with 30 feature attributes.
## Acknowledgments
A special thanks to Kaggle for providing the dataset and to the open-source community for developing tools and frameworks that enable machine learning research and applications.
