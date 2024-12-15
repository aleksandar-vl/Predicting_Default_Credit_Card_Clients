My forest_classifier is too big so I will have to review/rerun thoroughly this project.

# Credit Card Default Prediction

## Overview

This project aims to predict the likelihood of a customer defaulting on their credit card payment next month using the UCI Default of Credit Card Clients Dataset. Various machine learning classification algorithms, including Decision Trees, Random Forests, Linear SVM, and AdaBoost, are trained and optimized. The project involves data preprocessing, exploratory data analysis (EDA), and model evaluation. The best-performing model is further improved through oversampling techniques to handle class imbalance, resulting in enhanced recall and overall performance. The project demonstrates the application of machine learning techniques to real-world financial data for credit risk assessment.

## Introduction

Credit risk/score or the probability of a client defaulting is an interesting topic. This project explores whether we can predict the default of a customer using the UCI Default of Credit Card Clients Dataset. The goal is to see if algorithms trained and tested on the available dataset can be accurate in predicting defaults.

## Data

The dataset used in this project is the UCI Default of Credit Card Clients Dataset. It contains 25 variables, including demographic information, credit card bill statements, and payment history.

## How to run

1. Clone the repository.

2. Install the required packages from requirements.txt.

3. Run the Jupyter notebook in the folder where the Notebook is located.

* NB - Please note that the packages in the requirements.txt file are as per the stable version at the time of writing the original project. You may need to update the packages based on the latest versions which might affect the code.

## Results

The project compares several classification algorithms, including Decision Trees, Random Forests, Linear SVM, and AdaBoost. The Decision Tree algorithm, further optimized through oversampling, provided the best results in terms of recall and overall performance.

* NB_1 - There's an inconsistency with the Random Forest algorithm scores quoted. A more thorough inspection is required as the saved trained model is currently too big to be uploaded as it is and a fix needs to be found for that as well as the inspection.

## Conclusion

The project successfully demonstrates that it is possible to predict the default of a customer to a certain extent given the available data. However, it cannot be predicted with 100% accuracy due to the limitations of the dataset and the propensity of lenders to avoid risk.

## References

1. For Pickle - [Save and Load Machine Learning Models in Python with scikit-learn](https://machinelearningmastery.com/save-load-machine-learning-models-python-scikit-learn/)
2. Numerous articles from datascience.stackexchange.com, medium.com, and materials from Softuni Machine Learning 2019 course.
