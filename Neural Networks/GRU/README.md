# Gated Recurrent Unit (GRU)

## Overview

Gated Recurrent Units (GRUs) are a type of RNN similar to LSTMs but with a simpler structure. They use gates to control the flow of information, but unlike LSTMs, they do not have a separate memory cell, which makes them faster to train.

## Where is it Used?

- **Sequential Data:** Similar to LSTMs, but in scenarios where a simpler model may suffice.
- **Text Processing:** Language modeling and translation.
- **Time Series Prediction:** Forecasting future values in a sequence.

## How Does it Work?

GRUs combine the input gate and forget gate into a single update gate, making them computationally less expensive than LSTMs while still addressing the vanishing gradient problem.
