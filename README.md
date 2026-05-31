# Binary-Classification-with-Neural-Networks-on-the-Census-Income-Dataset

## Project Summary
This project develops a binary classification system that predicts whether a person’s annual income exceeds $50,000 using census-related information. The implementation uses the UCI Adult Census Income dataset and is built with PyTorch. The neural network combines embedding layers for handling categorical data and batch normalization for continuous numerical features.

## Main Highlights
Preprocessing of data through categorical encoding and tensor transformation.


Neural network architecture designed with embedding layers for categorical attributes.


Model training performed using Cross-Entropy Loss and the Adam optimization algorithm.


Performance evaluation using a separate test dataset with accuracy measurement.


Interactive prediction system that allows users to enter their own details for income prediction.


Graphical visualization of training loss across epochs.
## Dataset Information

Dataset Source: UCI Machine Learning Repository – Adult Census Income Dataset


Total Records: 30,000 cleaned entries without missing values


### Input Features:

5 categorical attributes

2 continuous numerical attributes

1 binary target variable
Objective: Determine whether a person earns more than $50K or not.

## Requirements

Software and Libraries

Python 3.x

PyTorch

pandas

numpy

scikit-learn

matplotlib

### Install Required Packages
```
pip install torch pandas numpy scikit-learn matplotlib
```

### How to Run the Project

Clone the Repository

Dataset Setup

Place the income.csv dataset file inside the Data folder before running the project.

Execute the Program.

### Run the Python scripts or Jupyter Notebook to:

preprocess the dataset,

train the neural network,

test the model performance,

And make predictions for new user inputs.

## Project Files Overview

data_preprocessing.py – Handles loading and preprocessing of the dataset.

model.py – Defines the PyTorch neural network model.

train.py – Executes the training process and stores model checkpoints.

evaluate.py – Tests the trained model and calculates evaluation metrics.

predict.py – Accepts user input and predicts income category.

notebook.ipynb – Provides a step-by-step implementation with explanations.

## Performance

Average testing accuracy reaches around 85%.

Training loss steadily decreases throughout approximately 300 epochs.

Embedding layers improve the handling of categorical variables efficiently.
## Possible Improvements

Test deeper neural network architectures and tune hyperparameters.

Include methods to manage missing data and class imbalance.

Deploy the solution as a web application or API for real-world use.
