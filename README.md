# Customer Behavior Prediction Model

## Overview
This project aims to predict customer behavior, focusing on predicting customer churn and conversion using a variety of machine learning models. The goal is to identify key features influencing customer behavior and create actionable insights for improving customer retention and marketing strategies.

## Dataset
The dataset contains customer purchase and interaction data, including features such as **Discount Applied**, **Purchase Amount (USD)**, **Age**, **Review Rating**, and **Frequency of Purchases**. These features were used to predict customer behavior, specifically whether they are likely to churn or convert.

## Key Features
- **Discount Applied**: Whether the customer applied a discount during their purchase.
- **Purchase Amount (USD)**: The amount spent by the customer during a transaction.
- **Age**: The age of the customer.

## Models Used
- **Logistic Regression**: A simple but powerful model for classification that was used to predict the likelihood of a customer churn based on the selected features.
- **Random Forest**: A robust ensemble method used to predict customer behavior while handling non-linear relationships.
- **Gradient Boosting**: Another powerful ensemble technique used for prediction, focusing on improving performance through successive trees.

## Results
- **Logistic Regression** achieved an accuracy of **82.99%** with both the full set of features and a reduced set of three features (Discount Applied, Purchase Amount, and Age).
- **Random Forest** achieved an accuracy of **80.85%** with the full set of features and **80.43%** with the reduced set, showing a minimal drop in performance when simplifying the model.
- **Feature Importance**: The most impactful features identified were **Discount Applied**, **Purchase Amount**, and **Age**, indicating that these variables strongly influence customer behavior and churn prediction.

## Conclusion
This analysis shows that focusing on **Discount Applied**, **Purchase Amount**, and **Age** allows for building a highly accurate predictive model while maintaining simplicity. The reduced model (Logistic Regression) performs just as well as the full model, making it an excellent choice for interpretability and deployment. The key takeaway is that **personalized discounts**, **purchase behavior monitoring**, and **age-based segmentation** can significantly enhance marketing efforts and customer retention strategies.

