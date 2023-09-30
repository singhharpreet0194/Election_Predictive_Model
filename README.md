# Election Analysis Project

## Introduction

🗳️ This project focuses on analyzing recent elections conducted by one of the leading news channels, CNBE. The goal is to build a model that predicts which party a voter will vote for based on provided information, ultimately creating an exit poll for predicting overall wins and seats covered by each party.

## Dataset

📊 The dataset 'Election_Data.xlsx' contains information from a survey conducted on 1525 voters, consisting of 9 variables.

## Project Files

📁 [Business Report - Ensemble.pdf](Business+Report_ensemble1.pdf)

📁 [Dataset: Election_Data.xlsx](Election_Data.xlsx)

📁 [Jupyter Notebook: Project_ensemble_1.ipynb](Project_ensemble_1.ipynb)

## Project Steps

### Data Ingestion

1.1 **Read the dataset.**
   - Perform descriptive statistics and check for null values. Provide inferences based on the findings.

1.2 **Perform Univariate and Bivariate Analysis.**
   - Conduct exploratory data analysis and check for outliers.

### Data Preparation

1.3 **Encode the data for Modeling.**
   - Determine if scaling is necessary. Split the data into training and test sets (70:30 ratio).

### Modeling

1.4 **Apply Logistic Regression and LDA.**
   - Implement Logistic Regression and Linear Discriminant Analysis.

1.5 **Apply KNN Model and Naïve Bayes Model.**
   - Apply K-Nearest Neighbors and Naïve Bayes models. Interpret the results.

1.6 **Model Tuning, Bagging, and Boosting.**
   - Fine-tune models, apply Bagging (Random Forest), and implement Boosting techniques.

1.7 **Performance Metrics.**
   - Evaluate predictions on both training and test sets using metrics like Accuracy, Confusion Matrix, ROC Curve, and ROC_AUC score. Compare models and provide insights on model optimization.

## Inference

1.8 **Based on these predictions, what are the insights?**
   - Provide insights based on the model predictions.

## 🚀 Conclusion

🗳️ This project aims to analyze recent elections and build predictive models to understand voter behavior. By employing various machine learning techniques, we strive to provide valuable insights to CNBE for better decision-making.

📊 Feel free to explore the project files, datasets, and business report provided to delve deeper into the analysis.

Happy Analyzing! 🗳️📊
