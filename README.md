# Titanic-Survival-Classification
A neural network model built with PyTorch to predict whether a Titanic passenger survived or not.
Results

Test Accuracy: 81.36%

Model Architecture

Input layer: 9 features
Hidden layer 1: 64 neurons (ReLU)
Hidden layer 2: 32 neurons (ReLU)
Output layer: 1 neuron (Sigmoid)
Loss: BCELoss
Optimizer: Adam (lr=0.001)

Data Preprocessing

Dropped irrelevant columns: PassengerId, Name, Ticket, Cabin
Filled missing Age values with median
Filled missing Embarked values with mode
Encoded Sex column (male=0, female=1)
One-hot encoded Embarked column
Normalized features with StandardScaler

Libraries

torch
pandas
scikit-learn

Dataset
Titanic dataset from Kaggle — 891 passengers, binary classification (0 = did not survive, 1 = survived)
