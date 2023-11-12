# Deep Learning Lab 1 README

**University:** Université Abdelmalek Essaadi  
**Faculty:** Faculté des Sciences et Techniques de Tanger  
**Department:** Génie Informatique  
**Master:** MBD  
**Course:** Deep Learning  
**Instructor:** Pr. Elaachak Lotfi  

## Lab Objective

The main purpose of this lab is to gain familiarity with the PyTorch library for handling Classification and Regression tasks by establishing Deep Neural Network (DNN) and Multi-Layer Perceptron (MLP) architectures.

## Part One: Regression

### Dataset
The dataset for the regression task can be found [here](https://www.kaggle.com/datasets/dgawlik/nyse).

1. **Exploratory Data Analysis (EDA):** Apply EDA techniques to understand and visualize the given dataset.
2. **Deep Neural Network Architecture:** Establish a DNN architecture using PyTorch for the regression task. Specify the hidden layers used in the architecture.
3. **Hyperparameter Tuning:** Use the GridSearch tool from the sklearn library to choose the best hyperparameters for an efficient model.
4. **Visualization:** Visualize the loss and accuracy graphs over epochs for both training and test data, and provide interpretations.
5. **Regularization Techniques:** Apply several regularization techniques on the architecture and compare the results with the initial model.

## Part Two: Multi-Class Classification

### Dataset
The dataset for the multi-class classification task can be found [here](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification).

1. **Data Pre-processing:** Apply pre-processing techniques to clean and standardize/normalize the data.
2. **Exploratory Data Analysis (EDA):** Apply EDA techniques to understand and visualize the given dataset.
3. **Data Augmentation:** Apply data augmentation techniques to balance the dataset.
4. **Deep Neural Network Architecture:** Establish a DNN architecture using PyTorch for the multi-class classification task. Specify the hidden layers used in the architecture.
5. **Hyperparameter Tuning:** Use the GridSearch tool from the sklearn library to choose the best hyperparameters for an efficient model.
6. **Visualization:** Visualize the loss and accuracy graphs over epochs for both training and test data, and provide interpretations.
7. **Metrics Calculation:** Calculate metrics like accuracy, sensitivity, F1 score, etc., on both training and test datasets.
8. **Regularization Techniques:** Apply several regularization techniques on the architecture and compare the results with the initial model.

## Example Results

- Regression Task:
  - Best hyperparameters: learning rate = 0.01, optimizer = Adam, epoch = 50, hidden layers = 64.
  - Initial Model Loss: 0.2, Initial Model Accuracy: 0.9
  - Regularized Model Loss: 0.15, Regularized Model Accuracy: 0.92

- Multi-Class Classification Task:
  - Best hyperparameters: learning rate = 0.001, optimizer = SGD, epoch = 30, hidden layers = 128.
  - Initial Model Accuracy: 0.85
  - Regularized Model Accuracy: 0.88

## Tools

- Kaggle
- GitHub
