# Supervised_Regression_SalaryPrediction
This project predicts salaries based on years of experience using supervised regression techniques. It includes data preprocessing, exploratory analysis, and modeling with Linear Regression, Decision Tree, and Random Forest. Evaluation uses MSE and R², with Python libraries like pandas, scikit-learn, and seaborn.

## Project Overview
The "Supervised-Salary-Prediction" project aims to develop a supervised regression model capable of predicting salaries based on historical data. The focus is on leveraging machine learning techniques to analyze features such as experience level, job title, and company location to provide accurate salary predictions.

## Project Goals
- Build a machine learning regression model to predict individual salaries based on various features.
- Evaluate and compare multiple regression algorithms to determine the most effective approach.

## Dataset
The project utilizes a dataset containing detailed job information, including:
- work_year: The year the job data pertains to.
- experience_level: The level of job experience (e.g., Junior, Senior).
- job_title: The job title.
- salary_in_usd: The annual salary in USD (target variable).
- remote_ratio: The percentage of remote work (0–100).
- company_location: The geographic location of the company.
- company_size: The size of the company (Small, Medium, Large).

## Models Used
Several machine learning algorithms were implemented and evaluated, including:
- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- Support Vector Regressor (SVR)
- XGBoost Regressor

## Results
The XGBoost model delivered the best performance among all tested models, achieving the following metrics:
- R² on training data: 31.81%
- R² on testing data: 26.52%
- Root Mean Squared Error (RMSE): $59,374

## Technologies Used
- Programming Language: Python
- Libraries:
  - Data Analysis: pandas, numpy
  - Visualization: matplotlib, seaborn
  - Machine Learning: scikit-learn, XGBoost
- Environment: Jupyter Notebook / Google Colab

## Key Features
- Outlier Handling: Ensures the model can manage extreme salary values without negatively impacting predictions.
- Model Comparison: Evaluates basic models like Linear Regression alongside advanced models like XGBoost.
- Interpretability: Provides insights into the impact of various features on salary predictions.

## Next Steps
- Feature Engineering: Incorporate additional relevant features such as industry, education level, or specific skillsets.
- Hyperparameter Tuning: Further optimize the selected models to improve performance.
- Deployment: Develop a web application (e.g., using Flask or Streamlit) to make the model accessible for real-world use.
