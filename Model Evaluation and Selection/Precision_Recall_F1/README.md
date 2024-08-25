# Precision, Recall, F1 Score

## Overview

Precision, recall, and F1 score are metrics used to evaluate the performance of classification models, especially in cases with imbalanced datasets. They provide insights into the model’s accuracy and robustness.

## Where is it Used?

- **Imbalanced Classification:** Evaluates performance where one class is much less frequent.
- **Model Comparison:** Helps in comparing models by examining their precision, recall, and F1 score.
- **Error Analysis:** Identifies and analyzes errors in the model's predictions.

## How Does it Work?

- **Precision** measures the accuracy of positive predictions: \[ \text{Precision} = \frac{TP}{TP + FP} \]
- **Recall** measures the ability to find all positive instances: \[ \text{Recall} = \frac{TP}{TP + FN} \]
- **F1 Score** is the harmonic mean of precision and recall: \[ \text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}} \]

Where:
- **TP** = True Positives
- **FP** = False Positives
- **FN** = False Negatives
