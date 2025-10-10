# AXIA-AFRICA-CAPSTONE-PROJECT
PREDICTING RESTAURANT , RECOMMENDATION AND ANALYSIS USING MACHINE LEARNING MODELS


This repository contains my final project for Axia Africa, completed in April 2025. The project involved working with a large restaurant dataset, where my main goal was to build a model to predict restaurant ratings and extract meaningful insights from the data. My regression model achieved an accuracy of 94%, with further details provided below.

**Dataset Summary**

9551 rows and 21 columns

9 missing values removed

No duplicate entries

**Descriptive Statistics**

Most common cuisine: North Indian (936 restaurants)

City with most restaurants: New Delhi (5,473 restaurants)

**Geospatial Analysis**

New Delhi had the highest number of restaurants (bar chart analysis)

Country-wise: Country code 1 had the most restaurants, followed by code 216

Correlation: No correlation between latitude and ratings; longitude shows a negative correlation

**Table & Online Booking Analysis**

12.12% of restaurants offer table booking; 25.66% offer online delivery

Average rating for restaurants with table booking: 3.44 vs 2.56 for those without

Online delivery performs best for medium-priced food range

**Price Analysis**

Restaurants with price rating 4 have the highest average rating (3.81)

Most restaurants have high average ratings

Most common price range :1

**Restaurant Insights**

Highest average ratings by cuisine: Italian

Most votes by cuisine: North Indian (53,747 votes)

Fast food shows consistent ratings

**Machine Learning Analysis**

Models used to predict restaurant aggregate ratings: Linear Regression, Decision Tree, Random Forest

Linear Regression: MSE ≈ 1.6276, R² ≈ 0.2893

Decision Tree: MSE ≈ 0.2070, R² ≈ 0.9096

Random Forest: MSE ≈ 0.1305, R² ≈ 0.9430 → Best performing model

**Libraries**
Pandas , Numpy , Seaborn , Matplotlib , Scikit-Learn

