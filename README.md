# Handwritten Digit Recognition Using Machine Learning

This repository contains a machine learning project focused on recognizing handwritten digits using classical and neural-based classification techniques but in a very simple way. The project compares multiple models using standardized evaluation metrics on a digit image dataset.

## 📊 Dataset
- **Name:** DIDA Dataset (10k version)
- **Source:** https://didadataset.github.io/DIDA/
- **Samples:** 10,000 images
- **Image Size:** 28 × 28 pixels
- **Classes:** Digits from 0 to 9
- **Input Format:** 784-dimensional vector per image

## 🎯 Project Objectives
- Implement and compare the following models:
  - Multi-layer Perceptron (Neural Network)
  - Linear Regression (One-vs-All)
  - Logistic Regression
  - Naive Bayes Classifier
- Evaluate models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

## ⚙️ Implementation Details

### 1. Data Preprocessing
- Normalize pixel values to the range [0, 1]
- Split data into:
  - 80% training
  - 20% testing

### 2. Neural Network
- Multi-layer Perceptron architecture
- At least two hidden layers
- Tunable hyperparameters:
  - Number of neurons
  - Learning rate
  - Epochs
  - Batch size

### 3. Linear Regression
- Implemented using One-vs-All strategy
- Adapted for multi-class classification

### 4. Logistic Regression
- Multi-class classification setup
- Convergence and regularization considerations

### 5. Naive Bayes
- Probabilistic classifier
- Assumes feature independence

## 📈 Evaluation & Analysis

### Cross-Validation
- 5-fold cross-validation
- Report mean and standard deviation of metrics

### Comparative Analysis
- Performance comparison across all models
- Training time vs accuracy trade-offs
- Computational efficiency analysis

## 🛠️ Tools & Libraries
- Python
- NumPy
- Scikit-learn

## 👤 Author
**Beshoy Gamal**  
Computer Science Student – Fayoum University
