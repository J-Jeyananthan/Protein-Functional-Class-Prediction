# Protein Functional Class Prediction

## Overview
This project aims to compare different machine learning models for predicting the functional class of a protein. The following models were implemented and compared:
- Random Forests
- Logistic Regression
- K-Nearest Neighbors

## Feature Engineering
The raw dataset used consisted of 1000 amino acid sequences and their corresponding functional classes. Sequence composition (percentage of given aa in each sequence) was extracted as a feature for this project.

## Results
![image](https://github.com/user-attachments/assets/831ab58a-d907-43cb-8360-fb0ad07ac97c)

Random forests showed the greatest accuracy, obtaining a score of 91%. Logistic regression achieved a particularly low accuracy of 28%, highlighting its limitations in capturing non-linear relationships.

## Future work
This project will be expanded by:
- Engineering new features 
- Implementing a neural network via PyTorch to compare performance to classical machine learning models

## Acknowledgements
Dataset was obtained from https://github.com/skpritch/Protein-Classification/tree/main. Dataset is not included in this repository due to licensing restrictions. 
