# 🐧 PCA + t-SNE on Palmer Penguins Dataset

## 📘 Course Assignment  
**Applied Machine Learning**  

---

## 📌 Overview  
This project explores **dimensionality reduction** techniques — Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) — on the **Palmer Penguins dataset**. The goal is to reduce feature space while retaining the underlying class structure, supporting better visualization and insight into the relationships among penguin species.

---

## 🧪 Methodology

### 1. 📥 Data Preparation
- Loaded and cleaned the penguins dataset
- Dropped missing values
- Normalized numerical features
- Encoded categorical variables

### 2. 📉 PCA: Principal Component Analysis
- Applied PCA to reduce dimensionality
- Visualized explained variance
- Plotted the first 2 and 3 components in 2D and 3D

### 3. 🌐 t-SNE: Nonlinear Projection
- Applied t-SNE to:
  - Raw data
  - PCA-reduced data
- Compared visualizations for cluster separation

---

## 📈 Key Insights

- PCA retained >95% variance with fewer components
- PCA+t-SNE showed the clearest species separation in 2D space
- Dimensionality reduction greatly improved cluster visibility without major loss of information

---

## 📁 Project Files
pca-tsne-penguins/
├── Assignment_1_Principal_Component_Analysis_(PCA).ipynb # Main notebook
├── cleaned_penguins.pkl # Cleaned and preprocessed dataset
├── pca_penguins.pkl # PCA-transformed data
├── tsne_penguins.pkl # t-SNE applied to original data
├── pca_tsne_penguins.pkl # t-SNE applied to PCA-reduced data
├── README.md # Project overview (this file)
