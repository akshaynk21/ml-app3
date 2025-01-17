# Practical Application 3

## Goal
The goal of the practical application 3 is to compare various classifiers on marketing data obtained from a bank. We explore various attributes that contribute to successful marketing campaign. The objective is to measure various models and compare their performance and accuracy of classification

## Notebook and Dataset
The notebook [bank.ipynb](bank.ipynb) contains the code and analysis of various modeling techniques. The dataset used is [bank-additional-full.csv](data/bank-additional-full.csv) 

## Findings
* All models performed better in terms of accuracy compared to the baseline model (DummyClassifier)
* SVM had good accuracy on both train and test data, but really lacked in performance compared to all other models
* DecisionTreeClassifier performed the best both in terms of performance and accuracy of predictions on test data.
* Different grid parameters were tried with each model. Due to limitation of computation resources, only a limited parameters were tried. The best parameters for each model are as follows
  * KNearestNeighbor : n_neighbors = 7
  * LogisticRegression : C = 1
  * SVC : C = 1; kernel = 'rbf'
  * DecisionTreeClassifier : max_depth = 5
