# GNN-AML: Explainable Anti-Money Laundering Detection with Graph Neural Networks

This repository contains the code, datasets, and research paper for the project **"Graph Neural Networks for enhancing Anti Money Laundering detection in Financial Transaction Systems."**

The framework models financial transactions as a dynamic graph to capture relational patterns and temporal sequences (layering) characteristic of money laundering, while providing explainable outputs for regulatory compliance.

## 🚀 Key Features
- **Dynamic Graph Modeling:** Captures the temporal evolution of transaction networks.
- **Class Imbalance Handling:** Uses graph-aware neighborhood sampling to mitigate extreme class imbalances.
- **Contrastive Learning:** Enhances temporal consistency of node embeddings.
- **Explainable AI:** Integrates GNN Explainer to highlight the suspicious subgraph and key features for each alert.

## 📊 Datasets
- **Elliptic Bitcoin Transaction Dataset:** [Download from Kaggle](https://www.kaggle.com/ellipticco/elliptic-data-set) or via `torch_geometric.datasets.Elliptic`.https://www.kaggle.com/datasets/algozee/credit-risk-and-loan-default-analysis-dataset?resource=download

## 🔧 Setup and Installation
(You will add your specific commands here, e.g., `pip install -r requirements.txt`)

## ▶️ How to Run
(You will add instructions for running your code from the Colab notebook)

## 📄 Paper
The full research paper, formatted in LaTeX, is available in the `paper/` directory of this repository:
- [View the paper on Overleaf](your-overleaf-link-here) (Provide a 'read-only' or 'edit' link as appropriate).
- Or download the PDF from the `paper/` folder.

## 🤝 Acknowledgments
This project was completed as part of the coursework for Dr. Usama Arshad at FAST NUCES, Islamabad.
