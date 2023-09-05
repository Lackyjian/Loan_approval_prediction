# Loan Approval Classification

![Loan Approval](https://www.mymudra.com/cms/public/storage/posts/August2023/LM0hIK79JRlolk22T2wa.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
The Loan Approval Classification project focuses on predicting loan approval decisions using machine learning models. Loan approval is a critical financial task, and accurate predictions can streamline the lending process and reduce risks. This project leverages machine learning to classify loan applications into approval or rejection categories.

## Dataset
The dataset used in this project was obtained from Kaggle and can be found at [Loan Approval Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset). It contains various features related to loan applicants, including attributes like income, credit history, loan amount, and more. The target variable is the classification of loan applications as approved or rejected.

## Models
We have trained several machine learning models to classify loan approval decisions. The following models were used:
- CatBoost Classifier
- LightGBM Classifier
- Random Forest Classifier
- XGBoost Classifier

These models were trained on the dataset to predict whether a loan application will be approved or rejected. To further improve the accuracy of predictions, a voting classifier was employed on these base classifiers to make the final predictions with remarkable accuracy.

## Usage
To use this project, follow these steps:
1. Clone this repository to your local machine.
2. Download the dataset from [Loan Approval Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset) and place it in the project directory.
3. Install the required Python libraries mentioned in code. 
4. Run the Jupyter notebook or Python script provided to train the models and make predictions.

## Results
The final accuracy achieved by this project is an outstanding 99.41%. This high accuracy demonstrates the effectiveness of machine learning in classifying loan approval decisions. The voting classifier, which combined predictions from multiple base classifiers, played a crucial role in achieving this remarkable accuracy.

## Contributing
Contributions to this project are welcome. If you have ideas for improving the models, optimizing the code, or adding new features, please feel free to submit a pull request.
