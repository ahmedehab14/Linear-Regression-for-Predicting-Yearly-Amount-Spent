# Customer Spending Prediction

## Overview

This project involves exploring customer data to understand the relationships between various features and the yearly amount spent by customers. The goal is to predict the yearly spending behavior based on user engagement and membership attributes. The analysis also serves as a foundation for further modeling and business insights.

## Business Requirements

1. **Understand Customer Spending Behavior:** Identify key factors influencing yearly spending based on user activity and membership details.
2. **Increase Customer Engagement:** Provide actionable insights for increasing user engagement, particularly focusing on app usage and membership duration.
3. **Enhance Revenue Strategies:** Utilize findings to enhance marketing, customer retention, and revenue-driving strategies.

## Dataset

The dataset contains the following features:

- **Avg. Session Length:** Average length of time a user spends on the platform during a session.
- **Time on App:** Total time spent on the mobile app by the user.
- **Time on Website:** Total time spent on the website by the user.
- **Length of Membership:** Duration of the user's membership (in years).
- **Yearly Amount Spent:** Total spending by the user in one year.

## Exploratory Data Analysis (EDA)

In the exploratory data analysis, we performed the following tasks:

1. **Data Distribution:** Analyzed the distribution of features such as Avg. Session Length, Time on App, Time on Website, Length of Membership, and Yearly Amount Spent.
2. **Correlation Analysis:** Identified key relationships between variables using pairplots to assess correlations, particularly focusing on how they influence the yearly spending.
3. **Insights:** Based on the analysis, we found that:
   - Length of Membership and Yearly Amount Spent have the strongest positive correlation.
   - Time on App also shows a moderate positive relationship with Yearly Amount Spent.
   - Time on Website and Avg. Session Length had weaker or no significant correlation with spending.

## Machine Learning Model

We used a regression model to predict the Yearly Amount Spent based on the features provided. The model's performance was evaluated using the following metrics:

- **Mean Absolute Error (MAE):** 8.43
- **Mean Squared Error (MSE):** 103.92
- **Root Mean Squared Error (RMSE):** 10.19

These metrics indicate that the model provides a reasonable approximation of yearly spending based on user features.

## Actionable Insights

1. **Focus on App Engagement:** To drive higher spending, strategies should aim to increase Time on App.
2. **Increase Membership Duration:** Longer membership durations correlate strongly with higher spending. Offering incentives to extend membership could boost revenue.
3. **Website Engagement:** Time on Website has a weaker correlation with spending, suggesting that app usage is a more critical area for improvement.

## Future Work

- **Model Improvement:** The model can be further improved by tuning hyperparameters, trying other regression techniques, or using machine learning algorithms like Random Forest or Gradient Boosting.
- **Additional Features:** Incorporating more features such as demographic data or user behavior patterns could further improve predictions.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
