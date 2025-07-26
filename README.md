# Student-Score-Prediction
# Overview
This project aims to build a machine learning model that predicts students' exam scores based on various performance factors such as hours studied, sleep hours, attendance, and more. The analysis leverages linear regression and polynomial regression, along with data preprocessing and performance evaluation techniques.

# Dataset
- Source: Kaggle - Student Performance Factors (https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)
- File: StudentPerformanceFactors.csv
- Target Variable: Exam_Score
- Features: Hours_Studied, Sleep_Hours, Attendance, and others.

# Objectives
1. Clean and explore the dataset.
2. Use Linear Regression to predict exam scores.
3. Evaluate model performance using Mean Squared Error (MSE) and R-squared (R²).
4. Visualize actual vs predicted results.
5. Apply Polynomial Regression for performance comparison.
6. Experiment with feature selection to evaluate impact on model performance.

# Tools & Libraries
- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

# Model Performance
- Full Linear Regression Model
  - MSE: 4.17
  - R²: 0.73
- Subset Linear Regression (Hours Studied, Sleep, Attendance)
  - MSE: 7.03
  - R²: 0.55
- Polynomial Regression (Degree 2)
  - MSE: 7.02
  - R²: 0.55

# Visualizations
- Actual vs Predicted (Full Linear Model)
- Linear vs Polynomial Regression Predictions (Subset)

# Future Improvements
- Apply Regularization (Lasso/Ridge)
- Use more advanced models (e.g., Decision Trees, Random Forest)
- Build a simple Web App with Streamlit for user interaction

