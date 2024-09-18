# Bayesian Network Classifier - Lab 4 (Q3)

## TEAM: GURUS
This project is part of **Lab 4, Question 3** for the **CS-367** course. It involves developing and evaluating a Bayesian Network classifier for a multi-feature dataset, which models the probabilistic relationships between features to make predictions.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)

## Introduction
The purpose of this project is to build a Bayesian Network classifier using a multi-feature dataset. The classifier is able to make predictions by explicitly modeling dependencies between features, unlike the Naive Bayes classifier which assumes feature independence. This flexibility allows for better predictive performance in cases where dependencies exist.

## Methodology

### 1. Bayesian Network Overview
A **Bayesian Network** is a probabilistic graphical model that represents a set of variables and their conditional dependencies via a Directed Acyclic Graph (DAG). Each node in the graph corresponds to a variable, and the edges represent dependencies.

### 2. Data Preprocessing
- The dataset is split into independent features `X` and target variable `y`.
- An 80/20 split is used to divide the dataset into training and testing sets.

### 3. Bayesian Network Construction
Steps involved in constructing the Bayesian Network:
1. **Identifying Dependencies**: The structure of the network is learned using algorithms like the **K2 algorithm** or constraint-based methods.
2. **Parameter Estimation**: Conditional probability distributions (CPDs) for each node are estimated using Maximum Likelihood Estimation.
3. **Model Representation**: The Bayesian Network is represented as a Directed Acyclic Graph (DAG) with nodes and edges.

### 4. Model Training and Prediction
- The model is trained using the training set.
- Predictions are made on the test set using the learned structure and CPDs.

### 5. Evaluation
- Model performance is evaluated using **accuracy**, which measures the percentage of correctly predicted class labels in the test set.

## Results
The Bayesian Network classifier achieved an accuracy of **98%**, demonstrating its ability to effectively model the relationships between the features and predict class labels.

## Conclusion
The Bayesian Network classifier offers a more flexible approach than the Naive Bayes classifier by explicitly modeling dependencies between features. In this experiment, the high accuracy (98%) reflects its ability to capture the underlying structure of the data.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/RamcharanSinghRamavath/CS-367-GURUS-Lab3-Q4.git
