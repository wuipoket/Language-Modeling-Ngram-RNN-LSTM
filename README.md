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
- N-gram Accuracy: 25.90% (Trigram)
- RNN Accuracy: 31.31%
- LSTM Accuracy: 32.38%
- LSTM achieves the lowest perplexity (49.01), indicating better sequence modeling capability

## Tech Stack
- Python
- PyTorch
- NumPy

## Key Takeaways
- Demonstrates progression from statistical to neural language models
- Highlights limitations of N-gram in long-context modeling
- Shows effectiveness of LSTM in capturing sequential dependencies
