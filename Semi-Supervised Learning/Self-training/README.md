# Self-training

## Overview
Self-training is a straightforward semi-supervised learning technique where a model is initially trained on a small set of labeled data. The model is then used to predict labels for the unlabeled data. The most confident predictions are added to the labeled dataset, and the model is retrained. This process is repeated iteratively.

### Where is it Used?

- **Text classification**: Enhancing models trained on a small set of labeled documents.
- **Speech recognition**: Leveraging small amounts of transcribed audio to improve recognition accuracy.
- **Image classification**: Improving performance with limited labeled images.

## How Does it Work?

- **Initial Training**: Train the model on the labeled dataset.
- **Label Prediction**: Use the trained model to predict labels for the unlabeled data.
- **Label Selection**: Select the data points where the model's predictions have the highest confidence.
- **Data Augmentation**: Add these confidently labeled data points to the labeled dataset.
- **Retraining**: Retrain the model with the augmented labeled dataset.
- **Iteration**: Repeat steps 2-5 until no significant improvement is observed.