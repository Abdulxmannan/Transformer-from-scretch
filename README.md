# Transformer from Scratch

## Overview

This project is an implementation of the Transformer model from scratch using PyTorch, inspired by the seminal "Attention is All You Need" paper. The goal was to build a deep understanding of the Transformer architecture and its core components, which have become foundational in modern Natural Language Processing (NLP) tasks like machine translation and text generation.

## Features
- **Self-Attention Mechanism**: Efficiently processes sequences by capturing dependencies between words at different positions.
- **Positional Encoding**: Ensures the model considers the order of words in a sequence.
- **Multi-Head Attention**: Enhances the model's ability to focus on different parts of the input.
- **Encoder-Decoder Architecture**: A full-fledged implementation, including both the encoder and decoder layers.

## Project Structure
- `transformer.py`: Core implementation of the Transformer model, including self-attention, multi-head attention, and feed-forward layers.
- `train.py`: Script for training the Transformer model with custom datasets.
- `utils.py`: Helper functions for data preprocessing, batching, and other utilities.
- `data/`: Sample dataset files and loading scripts.

## Dependencies

Before running the project, make sure to install the required dependencies:

```bash
pip install -r requirements.txt
