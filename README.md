# 🧬 High-Dimensional Cancer Data Visualization  
### Comparing PCA, t-SNE, UMAP, MDS, and ISOMAP  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2+-orange)](https://scikit-learn.org/)
[![UMAP](https://img.shields.io/badge/UMAP-0.5-green)](https://umap-learn.readthedocs.io/)
[![License](https://img.shields.io/badge/License-MIT-purple)](LICENSE)

![UMAP Visualization Example](https://via.placeholder.com/800x400/EFEFEF/AAAAAA?text=UMAP+Clustering+of+TCGA-PANCAN+Data)  
*(Example output: UMAP projection of 5 cancer types from 20,531 genomic features)*

---

## 🚀 Overview  
This project visualizes the **TCGA-PANCAN cancer dataset** (801 samples × 20,531 genes) using five dimensionality reduction techniques:  
- **PCA** (Principal Component Analysis)  
- **t-SNE** (t-Distributed Stochastic Neighbor Embedding)  
- **UMAP** (Uniform Manifold Approximation and Projection)  
- **MDS** (Multi-Dimensional Scaling)  
- **ISOMAP**  

**Goal**: Transform high-dimensional genomic data into 2D/3D plots to reveal hidden patterns in cancer subtypes.

---

## 🔍 Key Insights  
| Method  | Speed  | Cluster Quality | Preserves Global Structure | Best For |
|---------|--------|------------------|----------------------------|----------|
| PCA     | ⚡⚡⚡⚡ | Moderate         | ✅✅✅✅                     | Linear data |
| t-SNE   | ⚡⚡     | Excellent        | ❌                         | Local patterns |
| UMAP    | ⚡⚡⚡   | Excellent        | ✅✅✅                      | Large datasets |
| ISOMAP  | ⚡⚡     | Good             | ✅✅                        | Non-linear manifolds |

**Finding**: UMAP achieves the best balance between cluster separation and computational efficiency.

---

## 🛠️ Installation  
```bash
git clone https://github.com/yourusername/cancer-data-visualization.git
cd cancer-data-visualization
pip install -r requirements.txt  # numpy, scikit-learn, umap-learn, matplotlib
