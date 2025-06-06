# GCN-Tree-Classification
This repository contains the implementation of a two-part graph learning task:

1. **Reproduce a standard GCN (Graph Convolutional Network)** using a benchmark graph classification dataset (e.g., MUTAG).
2. **Adapt the model to work with tree-structured graphs** by creating a custom dataset and training a GCN to classify trees based on their structure.

## Objective

The purpose of this project is to understand how GCNs work for graph-level tasks and to explore their behavior on structured trees.

## Datasets Used

- **MUTAG**: A standard dataset for graph classification from TUDataset (Phase 1).
- **Synthetic Tree Dataset**: Created manually for this task, consisting of 100 graphs representing binary trees and linear trees with binary labels.

## Model

A GCN model is implemented with two graph convolution layers and a global mean pooling layer to produce graph-level embeddings. The final classification is done via a fully connected linear layer.

## Results

- The model achieves **>90% accuracy** on the synthetic tree dataset.
- Successfully demonstrates the adaptation of GCNs to structured trees.
