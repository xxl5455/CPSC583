# Optimizing GNN Performance with Random Forest Feature Selection

## Overview

This repository focuses on optimizing Graph Neural Network (GNN) performance by integrating Random Forest for feature selection. The project explores how leveraging feature selection techniques can improve GNN models' efficiency and accuracy in document classification tasks.

## Key Features

Feature Selection: Utilizes Random Forest to identify the most important features before GNN processing.

Baseline Models: Implements Graph Convolutional Networks (GCNs) and GraphSAGE as baseline GNN models.

Performance Comparison: Evaluates the impact of feature selection on training metrics (accuracy, precision, recall, F1-score).

Dataset Support: Supports datasets like Cora and CiteSeer for document classification tasks.

## Usage

1. Training and Evaluation

Run the corresponding notebook to preprocess the data, apply feature selection, train the GNN model, and evaluate its performance.

For the Cora dataset, use:
```
rf-cora2.ipynb
```

For the CiteSeer dataset, use:
```
RF_citeseer.ipynb
```

Each notebook contains the end-to-end pipeline, including data loading, feature selection, model training, and evaluation.

2. Feature Selection

Random Forest is used to identify the most relevant features for training the GNN model. The selected features are saved into a processed dataset file for further use.

3. Model Evaluation

Performance metrics (e.g., accuracy, precision, recall, F1-score) are displayed during training and logged at the end of each run.


