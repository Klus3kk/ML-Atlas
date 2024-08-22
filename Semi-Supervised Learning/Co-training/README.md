# Co-training

## Overview

Co-training is a semi-supervised learning method that requires multiple views of the data, typically from different feature sets. Two or more classifiers are trained on these different views. Each classifier is used to label the unlabeled data, and the newly labeled data is then added to the training set of the other classifier.

### Where is it Used?

- **Web page classification**: Using both text content and hyperlink structure as separate views.
- **Video analysis**: Leveraging visual and audio features to improve classification accuracy.

## How Does it Work?

- **Feature Split**: Split the feature set into two or more views.
- **Initial Training**: Train two separate models on different views of the labeled data.
- **Label Prediction**: Each model predicts labels for the unlabeled data.
- **Label Exchange**: Confident predictions from one model are added to the training set of the other model.
- **Retraining**: Retrain each model on its augmented labeled dataset.
- **Iteration**: Repeat steps 3-5 until convergence.