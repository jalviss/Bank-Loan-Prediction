# Bank-Loan-Prediction

## Introduction
This repository contains the completed tasks a loan approval prediction application using a Back Propagation Neural Network (BPNN) project. The project was completed as part of a deep learning course focuses on different aspects of neural network implementation and optimization.

## Task: Loan Approval Prediction (BPNN)

### Project Description
This project aims to create an application that determines whether a loan application should be accepted or rejected. The dataset used for this task contains various features relevant to loan applications.

### Steps and Solutions

1. **Data Preprocessing**
   - **Problem Identification and Approach**: The dataset had issues such as missing values, outliers, and heterogeneous data types. We handled missing values using imputation methods, treated outliers using scaler, and change data type.
   
2. **Data Exploration and Splitting**
   - **Exploratory Data Analysis (EDA)**: EDA is performed to understand the distribution and relationships in the data. The dataset was then split into training (80%), validation (10%), and test (10%) sets.

3. **Baseline BPNN Architecture**
   - The baseline model consisted of an input layer with 'n' nodes, two hidden layers with 2*n nodes each, and an output layer matching the number of classes. ReLU was used as the activation function for the hidden layers.

4. **Model Optimization**
   - I experimented with the architecture by adding/removing layers, tuning hyperparameters, and using techniques like dropout and batch normalization to improve accuracy. Adjustments were made based on challenges identified in the data, ensuring improved handling of feature variability and class imbalance.

5. **Performance Evaluation**
   - The models were evaluated on the test set using accuracy, precision, recall, and F1-Score. Detailed explanations of the results and comparisons between the baseline and optimized models were provided.
    Performance Evaluation
        The models were evaluated on the test set using accuracy, precision, recall, and F1-Score. Detailed explanations of the results and comparisons between the baseline and optimized models were provided.
