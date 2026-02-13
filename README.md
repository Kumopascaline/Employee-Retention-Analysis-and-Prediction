# Employee Retention Analysis and Prediction

This project explores the factors that influence employee turnover and builds a machine learning model to predict whether an employee is likely to leave the company.

## Overview

Using a dataset of employee metrics (satisfaction, hours worked, salary, etc.), this analysis identifies key "churn" drivers and utilizes Logistic Regression to achieve a predictive accuracy of approximately **77%**.

## Key Features of the Analysis

1. **Exploratory Data Analysis (EDA):** Identifying variables with direct impact on retention (e.g., satisfaction level and promotions).
2. **Visualizations:** Bar charts illustrating how salary levels and specific departments correlate with employee turnover.
                        <img width="859" height="547" alt="output" src="https://github.com/user-attachments/assets/281b76d1-298c-40ed-a562-7ec2c380f89d" />

<img width="1014" height="609" alt="output2" src="https://github.com/user-attachments/assets/185fa1f6-397b-4e3e-9022-2e097e1064f8" />

3.. **Predictive Modeling:** A Logistic Regression model trained on high-impact features.
4.. **Performance Evaluation:** Accuracy scoring and coefficient analysis to determine the weight of each factor.

## Prerequisites

To run the code provided in this repository, you will need the following Python libraries:

* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`

## How to Use

1. **Data:** Ensure the file `HR_comma_sep 1.xlsx - in.csv` is in your working directory or uploaded to your Google Colab environment.
2. **Execution:** Run the provided code blocks sequentially to perform the analysis and train the model.
3. **Interpretation:** * **Negative Coefficients** (like Satisfaction): As these increase, the likelihood of leaving decreases.
* **Positive Coefficients** (like Low Salary): As these increase, the likelihood of leaving increases.



## Results

* **Top Predictor:** Employee Satisfaction level.
* **Model Accuracy:** ~76.76% accuracy on the test dataset.
