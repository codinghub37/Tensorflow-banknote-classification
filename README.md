#  Bank Note Authentication Using TensorFlow Deep Neural Network

## Project Overview

This project demonstrates the implementation of a Deep Neural Network (DNN) using TensorFlow for Bank Note Authentication.

The objective is to classify bank notes as:

- Authentic (1)
- Fake (0)

using statistical features extracted from banknote images.

The project covers the complete machine learning workflow including:

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Deep Neural Network Development
- Model Training
- Model Evaluation
- Performance Comparison with Random Forest

---

# Dataset Information

Dataset: Bank Note Authentication Dataset

The dataset contains features extracted from images of genuine and forged banknotes.

### Features

- Variance
- Skewness
- Curtosis
- Entropy

### Target Variable

Class

- 0 = Fake Bank Note
- 1 = Authentic Bank Note

---

# Technologies Used

- Python
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

# Project Workflow

## Step 1: Import Libraries

Required libraries are imported for:

- Data Analysis
- Visualization
- Deep Learning
- Machine Learning

---

## Step 2: Load Dataset

The dataset is loaded using Pandas.

Purpose:

- Read bank note data
- Explore dataset structure

---

## Step 3: Exploratory Data Analysis (EDA)

The following visualizations are created:

### Count Plot

Shows distribution of:

- Authentic Notes
- Fake Notes

### Pair Plot

Shows relationships between features and class labels.

Purpose:

- Understand data patterns
- Detect class separation

---

## Step 4: Data Preparation

Features and labels are separated.

### Features (X)

- Variance
- Skewness
- Curtosis
- Entropy

### Labels (y)

Class

---

## Step 5: Feature Scaling

StandardScaler is used to normalize feature values.

Purpose:

- Improve neural network performance
- Faster convergence

---

## Step 6: Train-Test Split

Dataset is divided into:

- Training Set
- Testing Set

Purpose:

- Train model on one set
- Evaluate on unseen data

---

## Step 7: Build Deep Neural Network

The TensorFlow Sequential model contains:

### Hidden Layer 1

10 Neurons

### Hidden Layer 2

20 Neurons

### Hidden Layer 3

10 Neurons

### Output Layer

1 Neuron

Sigmoid Activation

Architecture:

Input Layer

↓

Dense(10)

↓

Dense(20)

↓

Dense(10)

↓

Dense(1)

---

## Step 8: Train Model

The neural network is trained using:

- Training Data
- Multiple Epochs
- Batch Processing

Purpose:

- Learn patterns from banknote features

---

## Step 9: Generate Predictions

Predictions are generated on test data.

Purpose:

- Determine whether a note is fake or authentic

---

## Step 10: Model Evaluation

Evaluation Metrics:

- Confusion Matrix
- Classification Report

Metrics Include:

- Accuracy
- Precision
- Recall
- F1 Score

---

## Step 11: Random Forest Comparison

A Random Forest Classifier is trained on the same dataset.

Purpose:

- Compare DNN performance
- Validate results

---

# Results

The Deep Neural Network successfully classifies bank notes as authentic or fake with high accuracy.

The Random Forest model is also evaluated for comparison.

---

# Installation

```bash
pip install -r requirements.txt
```

---

# Run Project

Open:

```bash
jupyter notebook "04-Tensorflow Project Exercise.ipynb"
```

Run all cells sequentially.

---

# Learning Outcomes

This project helps understand:

- Deep Neural Networks
- TensorFlow
- Data Preprocessing
- Feature Scaling
- Classification Problems
- Model Evaluation
- Random Forest Comparison

---

# Future Improvements

- Hyperparameter Tuning
- Cross Validation
- More Complex Neural Networks
- Model Deployment
- Web Application Integration

---

# Conclusion

This project demonstrates how TensorFlow Deep Neural Networks can be used to solve binary classification problems. The model effectively distinguishes between authentic and fake bank notes using extracted statistical features.

---

# Author

Machine Learning and Deep Learning Project
