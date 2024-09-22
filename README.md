# Machine Learning Models from Scratch

This repository contains implementations of various Machine Learning (ML) algorithms and neural network concepts from scratch using Python. The purpose of this project is to gain a deeper understanding of how these algorithms work behind the scenes by building them without using libraries like `scikit-learn` or `TensorFlow` for the core functionalities.

## Repository Contents

Here’s a brief overview of the files and notebooks available in this repository:

### Machine Learning Algorithms
1. **KFold.ipynb**
   - Implementation of K-Fold Cross-Validation.

2. **kmeans_with_kmeans++.ipynb**
   - K-Means Clustering algorithm with the K-Means++ initialization to improve cluster assignment.

3. **knn.ipynb**
   - Implementation of the K-Nearest Neighbors (KNN) classification algorithm.

### Neural Networks from Scratch

1. **ShallowNetwork.ipynb**
   - A basic single-layer neural network built from scratch using numpy, showcasing forward and backward propagation.

2. **l_layered_network.ipynb**
   - Implementation of a fully connected deep neural network with multiple hidden layers, forward/backward propagation, and parameter updates.

3. **logistic_regression.ipynb**
   - Implementation of Logistic Regression using gradient descent for binary classification tasks.

4. **logistic_regression_Adam.ipynb**
   - Logistic Regression using the Adam optimization algorithm for improved convergence.

5. **logistic_regression_mini_batch.ipynb**
   - Logistic Regression with Mini-Batch Gradient Descent, demonstrating the efficiency of batch processing over large datasets.

### Dataset Files

1. **train_catvnoncat.h5**
   - Training dataset used for classifying cat vs. non-cat images.

2. **test_catvnoncat.h5**
   - Test dataset used for validating the cat vs. non-cat classifier.
