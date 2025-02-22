# Customer Behavior Prediction Model

## Overview
This project aims to predict customer behavior, focusing on predicting customer churn and conversion using a variety of machine learning models. The goal is to identify key features influencing customer behavior and create actionable insights for improving customer retention and marketing strategies.

## Dataset
The dataset contains customer purchase and interaction data, including features such as **Discount Applied**, **Purchase Amount (USD)**, **Age**, **Review Rating**, and **Frequency of Purchases**. These features were used to predict customer behavior, specifically whether they are likely to churn or convert.

## Key Features
**Age**: The age of the customer, providing demographic information for segmentation and targeted marketing strategies.

**Gender**: The gender identification of the customer, a key demographic variable influencing product preferences and purchasing patterns.

**Item Purchased**: The specific product or item selected by the customer during the transaction.

**Category**: The broad classification or group to which the purchased item belongs (e.g., clothing, electronics, groceries).

**Purchase Amount (USD)**: The monetary value of the transaction, denoted in United States Dollars (USD), indicates the cost of the purchased item(s).

**Location**: The geographical location where the purchase was made, offering insights into regional preferences and market trends.

**Size**: The size specification (if applicable) of the purchased item, relevant for apparel, footwear, and certain consumer goods.

**Color**: The color variant or choice associated with the purchased item, influencing customer preferences and product availability.

**Season**: The seasonal relevance of the purchased item (e.g., spring, summer, fall, winter), impacting inventory management and marketing strategies.

**Review Rating**: A numerical or qualitative assessment provided by the customer regarding their satisfaction with the purchased item.

**Subscription Status**: Indicates whether the customer has opted for a subscription service, offering insights into their level of loyalty and potential for recurring revenue.

**Shipping Type**: Specifies the method used to deliver the purchased item (e.g., standard shipping, express delivery), influencing delivery times and costs.

**Discount Applied**: Indicates if any promotional discounts were applied to the purchase, shedding light on price sensitivity and promotion effectiveness.

**Promo Code Used**: Notes whether a promotional code or coupon was utilized during the transaction, aiding in the evaluation of marketing campaign success.

**Previous Purchases**: Provides information on the number or frequency of prior purchases made by the customer, contributing to customer segmentation and retention strategies.

**Payment Method**: Specifies the mode of payment employed by the customer (e.g., credit card, cash), offering insights into preferred payment options.

**Frequency of Purchases**: Indicates how often the customer engages in purchasing activities, a critical metric for assessing customer loyalty and lifetime value.

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

**Data Link**
https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset
