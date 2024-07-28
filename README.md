# AI Project (SVM)

## Overview

This project explores the use of Support Vector Machines (SVM) on various datasets with different levels of complexity. It includes an analysis of the impact of data complexity on SVM core selection and parameter tuning. Additionally, the project applies SVM with Principal Component Analysis (PCA) for dimensionality reduction on the fashion-mnist dataset.

## Part 1: SVM on Synthetic Datasets

### 1. Generating Datasets
We created three types of datasets:
- **Simple Problem (Linearly Separable)**
- **Medium Problem (Non-Linearly Separable, Moon Shapes)**
- **Complex Problem (Non-Linearly Separable, Circular Shapes)**

### 2. Training SVM Models
We trained SVM models with different kernels on these datasets:
- **Linear Kernel**
- **Radial Basis Function (RBF) Kernel**
- **Polynomial Kernel**

### 3. Analysis
The project includes a detailed analysis of SVM performance on different data complexities, examining the effects of kernel selection and parameter tuning.

## Part 2: SVM with PCA on Fashion-MNIST

### 1. Data Preparation
- Loaded the fashion-mnist dataset.
- Normalized the data.
- Split the data into training and validation sets.

### 2. Dimensionality Reduction
- Applied PCA to reduce the dimensionality of the dataset to 100 components.

### 3. Training and Evaluation
- Trained an SVM model with an RBF kernel on the reduced dataset.
- Evaluated the model's performance on training, validation, and test sets.
- Achieved the following accuracy scores:
  - **Training Accuracy:** 94.26%
  - **Validation Accuracy:** 90.6%
  - **Test Accuracy:** 90.23%

### 4. Confusion Matrix and Example Predictions
- Displayed a confusion matrix to visualize the model's performance.
- Showed 10 example images with their actual and predicted labels.

## Part 3: SVM on Iranian Car Plate Dataset

### 1. Dataset Description
- Images of some alphabets and numbers from Iranian car plates.
- Labels include: `ص`, `س`, `2`, `3`, `7`.

### 2. Training SVM Models
- Trained SVM models to recognize and classify the car plate characters.

### 3. Evaluation
- Evaluated the performance of the SVM models in recognizing the correct labels.

## Live Link
Check out the project [here](https://kiana8181.github.io/AI-Project-SVM-/).

## Dependencies
- Python libraries: `cv2`, `matplotlib`, `numpy`, `pandas`, `seaborn`, `sklearn`
