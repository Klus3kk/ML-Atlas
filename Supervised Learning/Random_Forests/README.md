# Random Forests

## Overview
Random Forest is an ensemble learning method that operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

### Where is it Used?
- **Fraud detection:** Identifying fraudulent transactions in finance.
- **Image classification:** Categorizing images into different classes.
- **Predictive modeling:** General-purpose algorithm for any tabular data.

## How Does it Work?
Random Forests improve the accuracy of decision trees by reducing overfitting through bootstrapping and aggregating the results of multiple trees. Each tree is trained on a random subset of data and features, hence the "random" in Random Forests.
