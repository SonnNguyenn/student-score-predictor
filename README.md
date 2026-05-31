# Student Score Prediction Using Machine Learning

## Project Overview

This project aims to predict students' mathematics exam scores using demographic and educational background information.

Unlike many score prediction projects, this study intentionally excludes reading and writing scores from the model inputs to avoid information leakage and create a more realistic prediction scenario.

## Dataset

Dataset: Students Performance in Exams

Target Variable:

* Math Score

Features:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course

Excluded Features:

* Reading Score
* Writing Score

## Project Workflow

1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Feature Encoding
4. Model Training
5. Model Evaluation
6. Model Interpretation

## Models Evaluated

| Model             | MAE   | MSE    | R²     |
| ----------------- | ----- | ------ | ------ |
| Linear Regression | 11.27 | 200.51 | 0.176  |
| Decision Tree     | 12.73 | 259.15 | -0.065 |
| Random Forest     | 12.40 | 247.47 | -0.017 |

## Best Model

Linear Regression achieved the highest R² score and was selected as the final model.

## Key Findings

* Standard lunch status showed the strongest positive association with math performance.
* Completing a test preparation course was associated with higher predicted scores.
* Demographic and educational background factors alone have limited predictive power.

## Conclusion

The model achieved an R² score of 0.176, indicating that demographic factors explain only a small portion of student performance.

This suggests that additional factors such as study habits, attendance, motivation, prior academic ability, and learning environment play a much larger role in determining math achievement.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook
