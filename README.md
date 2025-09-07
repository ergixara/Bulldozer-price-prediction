# Predicting the Sale Price of Bulldozers

This project demonstrates an **end-to-end machine learning workflow** for predicting the future sale prices of bulldozers based on historical auction data. It is built around the [Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers) Kaggle competition.

---

## Overview

The project follows a structured machine learning process:

- **Problem Definition** – Can we accurately predict the sale price of a bulldozer given its characteristics and historical sales data?  
- **Data** – Multiple datasets provided by Kaggle:  
  - `Train.csv`: Training set (sales up to 2011)  
  - `Valid.csv`: Validation set (Jan 2012 – Apr 2012, public leaderboard)  
  - `Test.csv`: Test set (May 2012 – Nov 2012, private leaderboard)  
- **Evaluation** – Models are evaluated using **Root Mean Squared Log Error (RMSLE)**, a metric that penalizes large under- or over-predictions.  
- **Feature Engineering** – Extracting useful information from timestamps, product categories, and other structured features.  
- **Model Building** – Training regression models (e.g., Random Forests, Gradient Boosting) to predict bulldozer prices.  
- **Model Tuning** – Hyperparameter optimization for better performance.  
- **Model Validation** – Checking results with cross-validation and comparing model performance.  
- **Insights** – Understanding which features drive bulldozer prices the most.  

---

## Tools Used

- **pandas**, **NumPy** for data manipulation  
- **Matplotlib**, **Seaborn** for visualization  
- **Scikit-Learn** for regression modeling and evaluation  

---

## Goal

- Build models that minimize RMSLE on validation data  
- Identify the key factors influencing bulldozer sale prices  
- Demonstrate a complete end-to-end regression machine learning workflow  

---

## References

- [Kaggle: Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers)
