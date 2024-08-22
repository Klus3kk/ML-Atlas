# k-Nearest Neighbors (k-NN)

## Overview
k-Nearest Neighbors is a simple, instance-based learning algorithm used for both classification and regression. It predicts the output for a given data point by finding the 'k' closest data points in the training set and taking a majority vote or average.

### Where is it Used?
- **Recommendation systems:** Finding similar users or items.
- **Pattern recognition:** Handwriting detection.
- **Genomics:** Classifying DNA sequences.

## How Does it Work?
k-NN works by storing all available cases and classifying new cases based on a similarity measure (e.g., distance functions like Euclidean distance). It is a lazy learner, meaning it doesn't learn a model from the training data but makes decisions based on the entire dataset.
