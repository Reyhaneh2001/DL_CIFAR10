# CIFAR-10 Image Classification with Deep Learning

## Project Overview
In this project, we will tackle the image classification task on the **CIFAR-10** dataset, which contains 60,000 32x32 color images across 10 different classes, with 6,000 images per class. Our goal is to build a deep learning model capable of classifying these images accurately using **Convolutional Neural Networks (CNNs)**.

## Approach
The approach involves several key steps:

1. **Data Preprocessing**:
    - Load the CIFAR-10 dataset.
    - Split the data into training, validation, and test sets.
    - Apply one-hot encoding to the labels for categorical classification.

2. **Model Construction**:
    - Build a **basic CNN model** with multiple convolutional, pooling, and dense layers.
    - Use **Keras Tuner** to perform hyperparameter optimization and tune the model architecture for better performance.

3. **Model Evaluation**:
    - Evaluate the performance of both the basic and the optimized models on the test set.
    - Compute evaluation metrics such as **Accuracy**, **F1-Score**, and **ROC AUC**.

4. **Wide & Deep Network**:
    - Explore a **Wide & Deep Network** model that combines wide and deep paths to improve feature extraction.

