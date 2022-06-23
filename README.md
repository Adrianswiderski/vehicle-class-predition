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

Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269
