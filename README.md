# Decision Tree Implementation

## Introduction

This repository contains an implementation of a decision tree algorithm in Python. The decision tree is a powerful non-parametric supervised learning algorithm used for classification and regression tasks. It works by recursively partitioning the dataset into subsets based on the features to create a tree-like model for making decisions.

## Requirements

- Python (version 3.6 or higher)
- NumPy
- pandas
- scikit-learn (optional, for comparison and evaluation)

## Installation

To use the decision tree implementation, simply clone this repository:

git clone https://github.com/Abdo55awad14/Decision-Trees.git


## Usage

You can use the decision tree implementation in your projects by importing the necessary files. Here's an example of how to use the decision tree algorithm:

```python
from decision_tree import DecisionTree

# Create an instance of the DecisionTree class
dt = DecisionTree()

# Train the decision tree on your dataset
dt.fit(X_train, y_train)

# Make predictions on the test set
predictions = dt.predict(X_test)

# Evaluate the model
accuracy = dt.evaluate(X_test, y_test)
print(f"Accuracy: {accuracy}")
