# Neural Network for Drug Side Effects Prediction

## Overview
This project develops and evaluates a neural network using TensorFlow/Keras to predict whether a patient may experience side effects from a drug.

The model is trained on synthetically generated data using age and weight as input features.

## Objectives
- Generate synthetic clinical-style data
- Build and compare neural network architectures
- Evaluate the effect of hyperparameters on performance
- Measure generalization on unseen test data
- Save and reload the best-performing model

## Methods
- Synthetic data generation
- Train/validation/test split
- MinMax normalization
- Dense neural networks with ReLU and Softmax
- Hyperparameter comparison across:
  - dataset size
  - hidden layer architecture
  - learning rate
  - loss function
  - epochs
  - batch size

## Evaluation
- Accuracy
- Weighted F1-score
- Confusion Matrix
- Classification Report
- Training/Validation loss curves
- Decision boundary visualization

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
