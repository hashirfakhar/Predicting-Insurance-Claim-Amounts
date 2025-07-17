# Task 4 – Predicting Insurance Claim Amounts

## Objective
The goal of this task is to predict medical insurance charges based on personal information such as age, BMI, smoking status, and region. Using the Medical Cost Personal Dataset, we perform exploratory data analysis, train a regression model, and evaluate its performance using standard error metrics.

## Approach
- Loaded and inspected the dataset (`insurance.csv`)
- Confirmed that there were no missing values
- Visualized key relationships between insurance charges and features like age, BMI, and smoking status
- Encoded categorical variables using:
  - Label Encoding for binary features
  - One-Hot Encoding for multiclass features
- Used a **Linear Regression** model to predict the target variable `charges`
- Evaluated model performance using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

## Results and Insights
- The Linear Regression model achieved:
  - **MAE:** 4181.19
  - **RMSE:** 5796.28
- Charges were significantly higher for smokers compared to non-smokers
- BMI and age also had a strong positive correlation with insurance costs
- Model performed reasonably well for a basic regression and could be improved with feature engineering or non-linear models

---
This task provided practical experience in regression modeling, error evaluation, and interpreting health-related cost data using real-world features.
