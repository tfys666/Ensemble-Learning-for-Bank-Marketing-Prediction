# Bank Marketing Prediction with Ensemble Learning

## Overview
This project predicts customer term deposit subscriptions using ensemble learning algorithms on Portuguese bank marketing data.

## Key Findings
- **Random Forest**: Best overall performance (AUC-ROC: 0.934, F1-Score: 0.618)
- **XGBoost**: Highest recall (0.847) and expected profit
- **Key Features**: Call duration, age, previous marketing outcomes, and macroeconomic indicators

## Models Compared
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost
- LightGBM

## Dataset
- Source: UCI Bank Marketing Dataset
- Records: 41,188 customers
- Period: May 2008 - November 2010
- Target: Term deposit subscription (yes/no)

## Methodology
1. Data preprocessing and feature engineering
2. Handling class imbalance (SMOTE + undersampling)
3. Hyperparameter optimization
4. Multi-dimensional evaluation

## Business Impact
- Improved marketing efficiency through targeted campaigns
- Data-driven customer segmentation
- Cost-benefit optimization for marketing strategies

## Technologies
- Python
- scikit-learn, XGBoost, LightGBM
- pandas, numpy
- matplotlib, seaborn

## Note
This is an academic project for demonstration purposes only.
