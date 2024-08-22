# Naive Bayes

## Overview
Naive Bayes is a probabilistic classifier based on Bayes' theorem with an assumption of independence between predictors. Despite its simplicity, it is effective in many real-world situations.

### Where is it Used?
- **Spam filtering:** Classifying emails as spam or not spam.
- **Sentiment analysis:** Determining the sentiment of text.
- **Document classification:** Categorizing articles by topic.

## How Does it Work?
Naive Bayes calculates the probability of a data point belonging to a particular class based on the Bayes theorem:
\[ P(C|X) = \frac{P(X|C) \cdot P(C)}{P(X)} \]
Where:
- \( P(C|X) \) is the posterior probability of class given predictors.
- \( P(X|C) \) is the likelihood of predictors given class.
- \( P(C) \) is the prior probability of class.
- \( P(X) \) is the prior probability of predictors.
