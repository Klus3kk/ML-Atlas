# Recurrent Neural Networks (RNN)

## Overview

Recurrent Neural Networks (RNNs) are designed for sequential data, where the output from the previous step is fed as input to the current step. They are effective for tasks where the order of inputs matters, such as time series prediction and language modeling.

## Where is it Used?

- **Time Series Forecasting:** Predicting stock prices, weather, etc.
- **Language Modeling:** Predicting the next word in a sentence.
- **Speech Recognition:** Converting spoken words into text.

## How Does it Work?

RNNs have a loop that allows information to persist, with each neuron passing its output as input to the next neuron in the sequence. This gives RNNs a "memory" of previous inputs in the sequence.
