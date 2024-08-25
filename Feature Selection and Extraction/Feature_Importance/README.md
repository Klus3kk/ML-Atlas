# Feature Importance from Random Forests

## Overview

Feature Importance from Random Forests measures the importance of each feature by evaluating how much each feature contributes to the reduction of the impurity in the decision trees of a random forest model.

## Where is it Used?

- **Model Interpretation:** Helps in understanding which features are most influential in making predictions.
- **Feature Selection:** Used to select the most important features for model training.
- **Feature Ranking:** Provides a ranking of features based on their importance.

## How Does it Work?

Random Forests compute feature importance by averaging the decrease in impurity (e.g., Gini impurity or entropy) across all trees in the forest. Features that lead to significant reductions in impurity are deemed more important.
