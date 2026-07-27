<h1 align="center">Stacked BiLSTMs for Text Generation</h1>
<p align="center"><img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/Keras-Latest-D00000?logo=keras&logoColor=white" alt="Keras"> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter"></p>
<p align="center">Character-level text generation using Stacked Bidirectional LSTMs trained on the Shakespeare corpus.</p>

---

## Overview

This project implements a deep recurrent neural network for generating Shakespeare-like text from scratch. It demonstrates how stacked LSTM architectures can learn sequential dependencies and produce coherent character-level outputs.

- **Dataset**: Tiny Shakespeare (raw text corpus)
- **Approach**: Character-level modeling with Stacked Bidirectional LSTMs
- **Goal**: Generate Shakespeare-style text from scratch

## Features

- Data preprocessing and character encoding
- Vocabulary creation and sequence preparation
- Stacked LSTM architecture with dropout for regularization
- Model checkpointing and early stopping
- Training history visualization (loss & accuracy curves)
- Text generation with temperature-based sampling

## Model Architecture

```
Embedding Layer (128-dim)  →  Maps characters to dense vectors
LSTM Layer 1 (256 units)   →  Bidirectional, return sequences
Dropout (0.2)
LSTM Layer 2 (256 units)   →  Bidirectional
Dropout (0.2)
Dense Layer (128, ReLU)
Dense Layer (Softmax)      →  Character probability distribution
```

> **Note**: Unidirectional LSTMs are used instead of Bidirectional for text generation because during inference only past characters are available. BiLSTMs would see future context during training that doesn't exist during generation, causing train-test mismatch.

## Results

The model learns Shakespearean language patterns including vocabulary, sentence structure, and rhythm. Temperature-based sampling allows control over creativity vs. coherence in generated text.
