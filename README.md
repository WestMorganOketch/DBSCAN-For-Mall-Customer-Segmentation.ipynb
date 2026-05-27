# 🛍️ DBSCAN Mall Customer Segmentation

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-DBSCAN-green.svg)](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)

Unsupervised customer segmentation using **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) on mall customer data. This project identifies natural customer groupings based on annual income and spending score, without assuming spherical clusters (unlike K-Means).

---

## 📊 Dataset

**Source:** `Mall_Customers.csv` (included in `data/` folder)  
**Features used:**
- `Annual Income (k$)`
- `Spending Score (1-100)`

The dataset contains 200 customer records. Other columns (Gender, Age) are not used for clustering in this notebook.

---

## 🧠 Why DBSCAN?

- Handles clusters of arbitrary shape.
- Automatically detects outliers (noise points).
- Does not require specifying number of clusters beforehand.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Git
- Jupyter Notebook / JupyterLab / VS Code

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/WestMorganOketch/DBSCAN-For-Mall-Customer-Segmentation.ipynb.git
   cd DBSCAN-For-Mall-Customer-Segmentation.ipynb