# nanoGPT

A lightweight implementation inspired by Andrej Karpathy's "Zero to Hero" tutorial.

## Overview

nanoGPT is a small-scale implementation of a Generative Pretrained Transformer (GPT) model. It follows the ideas presented in the paper "Attention is All You Need" and the design principles of OpenAI's GPT-2 and GPT-3 models.

## Implementation 

- Built with PyTorch
- Includes the following core components:
  - **Token and Positional Embeddings**: Maps input text into a continuous vector space.
  - **Transformer Blocks**: Incorporates self-attention and feed-forward networks.
  - **Layer Normalization**: Stabilizes training and enhances performance.
  - **Feed-Forward Neural Networks**: Adds non-linear transformations.
  - **Softmax Output Layer**: Predicts the next token in a sequence.

## References

- Vaswani, A., et al. (2017). *Attention is All You Need*.
- OpenAI's GPT-2 and GPT-3 papers.
- Andrej Karpathy's [Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) YouTube series.
