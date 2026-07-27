# Stacked LSTMs for Text Generation

This project implements a **Stacked LSTM** model for **character-level text generation** using the famous **Tiny Shakespeare** dataset.  
It demonstrates how deep recurrent neural networks can learn sequential dependencies and generate new text in the style of the training data.

## 📜 Project Overview

- **Dataset**: [Tiny Shakespeare](https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt)  
- **Approach**: Character-level modeling using Stacked Unidirectional LSTMs  
- **Framework**: TensorFlow/Keras  
- **Goal**: Generate Shakespeare-like text from scratch by training on character sequences.

## 🚀 Features

- Data preprocessing and character encoding  
- Vocabulary creation and sequence preparation  
- Stacked **LSTM** architecture with dropout for regularization  
- Model checkpointing and early stopping  
- Training history visualization (loss & accuracy curves)  
- Text generation with temperature-based sampling

## 📊 Model Architecture

- Embedding Layer (128-dim) – Maps characters to dense vectors
- LSTM Layer 1 – 256 units, return sequences
- Dropout (0.2)
- LSTM Layer 2 – 256 units
- Dropout (0.2)
- Dense Layer (128 units, ReLU)
- Dense Layer – Softmax activation for character prediction

> **Note**: Unidirectional LSTMs are used instead of Bidirectional LSTMs because text generation is an autoregressive task — at inference time, only past characters are available. BiLSTMs would see future context during training that doesn't exist during generation, causing a train-test mismatch.
