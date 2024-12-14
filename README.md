# Optimizing GNN Performance with Random Forest Feature Selection

## Overview

This repository focuses on optimizing Graph Neural Network (GNN) performance by integrating Random Forest for feature selection. The project explores how leveraging feature selection techniques can improve GNN models' efficiency and accuracy in document classification tasks.

## Key Features

Feature Selection: Utilizes Random Forest to identify the most important features before GNN processing.

Baseline Models: Implements Graph Convolutional Networks (GCNs) and GraphSAGE as baseline GNN models.

Performance Comparison: Evaluates the impact of feature selection on training metrics (accuracy, precision, recall, F1-score).

Dataset Support: Supports datasets like Cora and CiteSeer for document classification tasks.

## Usage

1. Feature Selection

Run the feature selection script to preprocess the data and extract important features:

python feature_selection.py

This step saves a new .pt file containing the filtered features.

2. Training

Run the training script with the updated dataset:

python train.py

This will train the GNN models (with and without feature selection) and log the performance metrics.

3. Model Evaluation

Performance metrics (e.g., accuracy, precision, recall, F1-score) are displayed during training and saved for each run.
