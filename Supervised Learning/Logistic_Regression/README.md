# Logistic Regression

## Overview
Logistic Regression is a classification algorithm used to predict a binary outcome (1/0, Yes/No, True/False) based on one or more independent variables. Unlike linear regression, it outputs a probability that is then mapped to two classes.

### Where is it Used?
- **Spam detection:** Classifying emails as spam or not spam.
- **Customer churn prediction:** Predicting whether a customer will leave or stay.
- **Disease prediction:** Predicting whether a patient has a certain disease based on their symptoms.

## How Does it Work?
Logistic Regression uses the logistic function to model a binary dependent variable:
\[ \text{logit}(p) = \log\left(\frac{p}{1-p}\right) = \beta_0 + \beta_1x_1 + ... + \beta_nx_n \]

Where:
- \( p \) is the probability of the outcome being 1.
- \( x_1, ..., x_n \) are the independent variables.
- \( \beta_0, \beta_1, ..., \beta_n \) are the coefficients.
