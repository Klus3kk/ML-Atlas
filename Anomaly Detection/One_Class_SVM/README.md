# One-Class SVM

## Overview

One-Class SVM is an algorithm used for anomaly detection where the model learns to recognize the distribution of a single class (normal) and identifies outliers as deviations from this distribution.

## Where is it Used?

- **Novelty Detection:** Identifies novel or rare events that deviate from the norm.
- **Fault Detection:** Detects defects in industrial systems.
- **Cybersecurity:** Finds unusual patterns in network activity.

## How Does it Work?

One-Class SVM creates a decision boundary that encompasses the majority of the training data. Points outside this boundary are considered anomalies.
