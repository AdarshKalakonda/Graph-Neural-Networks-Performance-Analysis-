# GNN Node Classification

This project analyzes the performance of Graph Neural Networks (GNNs) models on node classification tasks across three popular datasets: **Cora**, **Pubmed**, and **Citeseer**. The following GNN models are implemented and evaluated:

- **GCN (Graph Convolutional Network)**
- **GAT (Graph Attention Network)**
- **GraphSAGE (Graph Sample and Aggregation)**

The performance of each model is evaluated based on accuracy, and the results are compared across all three datasets using **Plotly** visualizations.

---

## Project Overview

The project performs the following steps:

1. **Load Datasets**  
   Load the **Cora**, **Pubmed**, and **Citeseer** datasets using `torch_geometric` library.

2. **Implement GNN Models**  
   Implement three GNN models:
   - **GCN**: Uses graph convolution layers for node classification.
   - **GAT**: Uses attention mechanisms for graph nodes to improve performance.
   - **GraphSAGE**: Samples and aggregates neighbor nodes for graph node learning.

3. **Train and Evaluate Models**  
   Each GNN model is trained on all three datasets, and their performance is evaluated based on classification accuracy.

4. **Visualize Results**  
   The performance of each model on each dataset is visualized using **Plotly**, with comparisons of the accuracy for each model across the datasets.

---

## Datasets

The following datasets are used for training and testing the models:

- **Cora**: A citation network dataset with 2708 scientific publications and 5429 citation links.
- **Pubmed**: A dataset containing 19717 scientific publications from the PubMed database.
- **Citeseer**: A dataset containing 3327 scientific publications classified into 6 categories.

These datasets are available in the **Planetoid** dataset collection of the `torch_geometric` library.

---

## Installation

To run this project on your local machine, you’ll need to install the required dependencies. You can create a virtual environment and install the necessary packages as follows:

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/GNN_Node_Classification.git
cd GNN_Node_Classification
