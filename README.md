# Language Modeling: N-gram, RNN, and LSTM

## Overview
This project implements and compares multiple language modeling approaches for next-token prediction, ranging from statistical models to neural network-based models.

## Methods

### N-gram Model
- Implemented bigram and trigram models from scratch
- Estimated probabilities using frequency counts

### RNN Model
- Implemented using PyTorch
- Used cross-entropy loss and Adam optimizer

### LSTM Model
- Extended RNN to handle long-term dependencies

## Experiments
- Evaluated using prediction accuracy and perplexity
- Performed sentence completion on incomplete sequences

## Results
- Neural models outperform N-gram in long-range dependencies
- LSTM achieves better performance than vanilla RNN

## Tech Stack
- Python
- PyTorch
- NumPy

## Key Takeaways
- Demonstrates progression from statistical to neural language models
