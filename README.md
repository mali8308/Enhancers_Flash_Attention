# Homework 3: Sequence Modeling for Enhancer Classification

**Course:** Deep Learning in Medicine – Spring 2025  
**Author:** Muhammad Ali

## Overview

This repository contains the implementation and results for **Homework 3**, focusing on **sequence modeling in biology** using deep learning. The central goal is to classify genomic **enhancer sequences** using modern deep learning architectures in PyTorch.

---

## Tasks

The homework is divided into four independent tasks:

### 1. RNNs / LSTMs for Sequence Classification (40 points)
- Implemented an LSTM model using PyTorch
- Trained on genomic sequence data to classify enhancer activity
- Evaluated model performance and limitations

### 2. Transformer-based Classification (40 points)
- Implemented a custom Transformer model with classification head
- Compared with LSTM in terms of:
  - Accuracy
  - GPU memory usage
  - Runtime performance
- Highlighted architectural strengths and weaknesses

### 3. Hyperparameter Optimization (30 points)
- Used a hyperparameter tuning library (e.g., Optuna or Ray Tune)
- Explored learning rate, number of layers, hidden size, and dropout
- Compared optimized Transformer with default configuration

### 4. Embedding Exploration from SSL Models (30 points)
- Loaded embeddings from a pretrained self-supervised learning (SSL) model
- Used dimensionality reduction (e.g., PCA or UMAP) for visualization
- Explored whether SSL embeddings separate enhancer vs non-enhancer sequences meaningfully

---

## Dataset

- Sourced from the [`genomic-benchmarks`](https://github.com/ML-Bioinfo-CEITEC/genomic_benchmarks) package
- Task: Binary classification of DNA sequences (enhancer vs. non-enhancer)
- Data format: FASTA-like sequences as strings (A, C, G, T)
