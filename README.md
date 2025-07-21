# Bullet Train Accident Survival Prediction using ANN

This project involves building an Artificial Neural Network (ANN) to predict the survival of passengers involved in a bullet train accident, based on various features such as class, age, gender, and fare.


## Problem Statement

Each row in the dataset represents a passenger on the bullet train. The objective is to predict the `Survived` column using the following features:

- **Pclass**: Passenger class (1 = Business, 2 = Lower Business, 3 = Economy)
- **Sex**: Gender
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Fare**: Ticket cost

The task is to preprocess this data, build an ANN model, tune its parameters (layers, neurons, epochs, batch size), and analyze its behavior.

## Tasks Completed

- Data preprocessing (handling missing values, encoding categorical data)
- ANN model built using TensorFlow/Keras
- Experimentation with:
  - Number of hidden layers
  - Number of neurons per layer
  - Batch size and epochs
- Performance evaluation (accuracy, loss trends)
- Analysis and answers to assignment questions

## Model Evaluation & Questions

A detailed response to the following questions is provided in `analysis_answers.txt`:

1. **Effect of increasing layers on execution time**
2. **Effect of increasing both neurons and layers**
3. **Final model architecture (layers and neurons) and justification**
4. **Epochs after which training stopped improving**
5. **Explanation of batch size and its effect on training**

##  How to Run

Make sure you have the required dependencies installed:

```bash
pip install numpy pandas tensorflow scikit-learn matplotlib


