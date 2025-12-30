# Electric Vehicle Price Prediction

## Overview
This project implements an end-to-end supervised machine learning pipeline to predict electric vehicle prices in Germany based on technical and performance specifications. The goal is to demonstrate the full data science workflow from raw data to an optimized predictive model.

## Problem Statement
Accurately predicting electric vehicle prices is important for both consumers and industry stakeholders. This project explores how vehicle specifications such as range, battery capacity, efficiency, and performance can be used to estimate market prices using machine learning.

## Dataset
The dataset contains electric vehicle specifications and pricing information for the German market, including:
- Battery capacity
- Driving range
- Efficiency
- Performance-related features
- Target variable: **Price in Germany**

## Methodology
The project follows a structured machine learning pipeline:
1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature engineering
4. Feature scaling
5. Train-test split
6. Model comparison
7. Hyperparameter tuning
8. Model evaluation and final selection

## Models Evaluated
- K-Nearest Neighbors (KNN)
- Decision Tree
- Gradient Boosting

After model comparison and tuning, **KNN** achieved the best performance.

## Final Model
- Model: Optimized K-Nearest Neighbors
- Best parameter: `n_neighbors = 3`
- Test Accuracy: **~94%**

## Key Takeaways
- Proper preprocessing and feature scaling significantly impact model performance.
- Simple models like KNN can outperform more complex ones when well-tuned.
- Vehicle technical specifications provide strong signals for price prediction.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Results
- Best performing model: K-Nearest Neighbors (KNN)
- Optimized hyperparameter: n_neighbors = 3
- Test accuracy: ~94%

## Future Improvements
- Testing additional regression models
- Incorporating market demand or sales data
- Extending the analysis to other European markets
