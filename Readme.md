# GNN-AML: Explainable Anti-Money Laundering Detection with Graph Neural Networks

This repository contains the code, datasets, and research paper for the project **"Graph Neural Networks for enhancing Anti Money Laundering detection in Financial Transaction Systems."**

The framework models financial transactions as a dynamic graph to capture relational patterns and temporal sequences (layering) characteristic of money laundering, while providing explainable outputs for regulatory compliance.

## 🚀 Key Features
- **Dynamic Graph Modeling:** Captures the temporal evolution of transaction networks.
- **Class Imbalance Handling:** Uses graph-aware neighborhood sampling to mitigate extreme class imbalances.
- **Contrastive Learning:** Enhances temporal consistency of node embeddings.
- **Explainable AI:** Integrates GNN Explainer to highlight the suspicious subgraph and key features for each alert.

## 📊 Datasets
- **Elliptic Bitcoin Transaction Dataset:** [Download from Kaggle](https://www.kaggle.com/ellipticco/elliptic-data-set) or via `torch_geometric.datasets.Elliptic`.https://www.kaggle.com/datasets/algozee/credit-risk-and-loan-default-analysis-dataset?resource=download.

## 🤝 Acknowledgments
This project was completed as part of the coursework for Dr. Usama Arshad at FAST NUCES, Islamabad.
