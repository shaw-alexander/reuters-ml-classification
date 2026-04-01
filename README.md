# Reuters Text Classification (Neural Network)

## Overview
This project builds a neural network to classify news articles into 46 topics using the Reuters dataset.

## Problem Type
Multiclass classification

## Dataset
- Source: TensorFlow Keras Reuters dataset
- Input: Articles vectorised into 10,000-dimensional binary vectors
- Output: 46 categories

## Model Architecture
- Dense (64 units, ReLU)
- Dropout (0.5)
- Dense (46 units, Softmax)

## Training Setup
- Loss: Categorical Crossentropy
- Optimiser: RMSprop
- Batch size: 512
- Validation split: 0.2

## Results
- Validation accuracy: ~81%
- Overfitting observed after ~10 epochs

## Key Learnings
- Dropout reduces overfitting but excessive values reduce model capacity
- Model performance depends heavily on regularisation balance

## Files
- reuters-classification.ipynb → full implementation
- report.html → final report (recommended view)
