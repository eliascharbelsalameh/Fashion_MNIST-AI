# Fashion-MNIST Project

## Overview
This project is a part of the GEL521 Machine Learning course. It involves the implementation of machine learning models on the Fashion-MNIST dataset, a popular dataset used for benchmarking image classification algorithms.

## Objectives
1. **Match the True Output**: The goal is to minimize mismatches between the predicted and actual values using Convolutional Neural Networks (CNN).
2. **Improve Accuracy**: Utilize Artificial Neural Networks (ANN) to achieve the highest possible accuracy, targeting around 90%.

## Proposed Solutions
The project explores three different approaches to solve the Fashion-MNIST classification problem:

1. **Solution 1: Using MLPClassifier**
   - Implementation of a Multi-Layer Perceptron (MLP) Classifier.

2. **Solution 2: Using Convolutional Neural Network (CNN)**
   - Implementation of a CNN using the Keras library.

3. **Solution 3: Custom Implementation**
   - Development of a custom ANN with the following features:
     - Categorical cross-entropy calculation
     - One-hot encoding
     - Batching
     - Modified network structure:
       - Learning Rate (LR): 0.01
       - Momentum Factor (MF): 0.9
       - Structure: [794, 1024, 1024, 512, 10]
       - Batch Size: 128
       - Epochs: 100
   - Achieved training accuracy: 99.61%

## Dataset
Fashion-MNIST is a dataset of Zalando's article images consisting of 60,000 training images and 10,000 test images, with 10 classes representing different types of clothing.

## Usage
To run the project:
1. Clone the repository.
2. Install the required dependencies.
3. Run the code for the selected model (MLPClassifier, CNN, or Custom ANN).
4. Evaluate the model's performance on the test set.

## Results
The custom ANN implementation achieved a training accuracy of 99.61%.

## Acknowledgments
We would like to thank Dr. Hayssam Serhan for his guidance throughout the course.
