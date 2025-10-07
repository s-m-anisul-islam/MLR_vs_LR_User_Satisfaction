# MLR_vs_LR_User_Satisfaction
Predicting software user satisfaction using Multiple Linear Regression (MLR) and Simple Linear Regression (LR) with Python. Includes exploratory data analysis, model evaluation, and visual comparison of predictions.


# Predicting User Satisfaction with Linear Regression

This repository demonstrates **predictive modeling of user satisfaction scores** using both **Multiple Linear Regression (MLR)** and **Simple Linear Regression (LR)**. The analysis revisits traditional regression concepts and applies them with the **latest Python libraries** for practical insights in software and IT analytics.

## Project Overview

- **Objective:** Predict a product's User Satisfaction Score based on key factors.
- **Independent Variables (MLR):**
  - Average Response Time (s)
  - Number of Features
  - Number of Bugs Reported
  - Training Hours Provided
- **Independent Variable (LR):** Product Quality (for simple linear regression)
- **Dependent Variable:** User Satisfaction Score
- **Evaluation Metrics:** MSE, RMSE, MAE, R²
- **Key Insights:**
  - MLR captures multiple influencing factors and improves predictive performance.
  - Visual comparison of predicted vs actual scores highlights model accuracy.

## Files in the Repository

| File | Description |
|------|-------------|
| `MLR_vs_LR_User_Satisfaction.ipynb` | Jupyter Notebook containing full analysis, plots, and evaluation metrics. |
| `MLR_vs_LR_User_Satisfaction_Output.pdf` | PDF export of the notebook with code, outputs, and visualizations. |
| `Synthetic_app_data.csv` | Sample dataset for MLR analysis. |
| `user_satisfaction.csv` | Sample dataset for LR vs MLR comparison. |

## Tools & Libraries

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (LinearRegression, train_test_split, evaluation metrics)

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/MLR_vs_LR_User_Satisfaction.git
