# vehicle-class-predition

# Purpose

The goal of the project was to create a model that predicts the class of a car, based on features extracted from the silhouette of the vehicle.


# Dataset
Data comes from https://www.openml.org/search?type=data&sort=runs&id=54&status=active. 
The collection has 846 examples and 19 features. It is divided into a train collection (676 examples) and a test collection (170 examples)


# Models
The project compared the performance of 3 models:
1. Logistic Regression (L1 regularization)
2. C-Support Vector Classification
3. Neural network (single layer feed forward network, optimizer - SGD, loss function - cross entropy)


# Evaluation

Model | Accuracy | Pracision | Rercall | F1-score
Logistic Regression | 0.835 | 0.832 | 0.835 | 0.831 
C-Support Vector Classification | 0.817 | 0.811 | 0.817 | 0.813 
Neural network | 0.776 | 0.774 | 0.776 | 0.775 
