# Classification-Model-Accuracy
# Data Science: MNIST Classification using k-Nearest Neighbors

Author: BARA AHMAD MOHAMMED

## Description
This code performs classification on the MNIST dataset using the k-Nearest Neighbors (kNN) algorithm. It loads the training and testing datasets, trains a kNN classifier on the training data, evaluates its performance on the testing data, and calculates the accuracy score. Additionally, it visualizes random samples of actual vs predicted labels using matplotlib.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>

## Usage

Ensure that the MNIST dataset files (mnist_train.csv and mnist_test.csv) are available in the project directory.
Run the code:
bash
Copy code
python mnist_classification.py
The accuracy score of the kNN classifier on the MNIST testing dataset will be printed.
A visualization showing random samples of actual vs predicted labels will be saved in the 'images' folder as 'mnist_classification_visualization.png'.
Files

mnist_classification.py: Python script containing the code for MNIST classification using kNN.
mnist_train.csv: CSV file containing the MNIST training dataset.
mnist_test.csv: CSV file containing the MNIST testing dataset.
Requirements

Python 3.x
pandas
scikit-learn
joblib
matplotlib
License

This project is licensed under the MIT License - see the LICENSE file for details.

