
# Multi-Class Classification with PyTorch

This project demonstrates a multi-class classification task using PyTorch. The goal is to classify data points into one of several classes based on their features.

## Overview

In this project, we:
1. **Generate Synthetic Data:** Use `make_blobs` from `sklearn` to create a dataset with 4 distinct classes.
2. **Build a Neural Network Model:** Define a simple feedforward neural network using PyTorch with two hidden layers.
3. **Train and Evaluate the Model:** Train the model using stochastic gradient descent and evaluate its performance on a test set. We calculate the accuracy and loss for both training and test sets.
4. **Visualization:** Plot the data distribution and the decision boundaries (if needed).

## Requirements

- Python
- PyTorch
- `matplotlib`
- `sklearn`

You can install the necessary Python packages using:

```bash
pip install torch matplotlib scikit-learn
```

## Usage

1. **Download Dependencies:** The script will automatically download a helper file (`helper_functions.py`) if it's not already present.
2. **Run the Script:** Execute the Python script to start training and evaluating the model.

## Code Overview

- **Data Generation:** Creates a dataset with 5000 samples, each with 2 features, and 4 distinct clusters.
- **Model Definition:** A feedforward neural network with 2 hidden layers.
- **Training Loop:** Runs for 10,000 epochs, computes loss and accuracy, and prints them every 10 epochs.
- **Evaluation:** Computes accuracy on test data and prints the results.

## Results

The model's performance is monitored through:
- Training and test loss
- Training and test accuracy

The output will show the loss and accuracy metrics at regular intervals.
