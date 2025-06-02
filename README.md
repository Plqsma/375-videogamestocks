# 375-videogamestocks
# Video Game Stock Price Prediction

## Overview
This project explores predictive modeling on the closing prices of the top 10 video game stocks. Two regression models — **Linear Regression** and **Random Forest Regressor** — were implemented to forecast stock prices based on historical features.

## Objectives
- Analyze trends in top video game company stock data.
- Build and evaluate regression models to predict closing prices.
- Compare model performance using metrics such as MSE and R².
- Provide insights on the effectiveness and trade-offs of different regression approaches.

## Tools & Technologies
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – regression modeling and evaluation

## Models Implemented
- **Linear Regression**  
  Pros: Interpretable, simple, and fast  
  Cons: Prone to underfitting, assumes linear relationships

- **Random Forest Regressor**  
  Pros: Handles non-linearity well, robust to overfitting  
  Cons: Less interpretable, computationally heavier

## Evaluation Metrics
- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**

These metrics were used to assess accuracy and explainability across the two models.

## 📌 Key Findings
- Random Forest generally provided better prediction accuracy but at the cost of interpretability.
- Linear Regression offered a good baseline and was useful for understanding feature relationships.
