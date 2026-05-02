# Predicting Sephora Product Popularity with Machine Learning

This project explores how supervised machine learning can be used to predict whether a beauty product will become a customer favorite on Sephora. By analyzing product information and customer review behavior, this project aims to understand what product characteristics are most associated with popularity.

Using over 8,000 Sephora products and 1 million+ customer reviews, I built classification models to predict whether a product would be considered popular or less popular based on customer engagement data. Products were labeled using loves_count, where products above the median were classified as popular.

I trained multiple supervised learning models, including Logistic Regression, Random Forest, and Gradient Boosting. The best-performing model was Random Forest, achieving 83.5% accuracy and a ROC AUC score of 0.92.

The analysis showed that features such as review activity, product rating, customer engagement, and brand-related signals were strong predictors of product popularity.

Read the full Medium post here:
👉 https://medium.com/@kousalyapotti/can-machine-learning-predict-which-sephora-products-become-customer-favorites-49fb673fe0d4

## Tools Used
### Programming
- Python
- Anthropic Claude Code
### Libraries
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
### Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
