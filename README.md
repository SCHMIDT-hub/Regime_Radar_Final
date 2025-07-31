# Regime_Radar_Final
# RegimeRadar — Week 3 Report

## 📅 Week 3 Overview

In Week 3, we focused on identifying distinct **market regimes** using unsupervised clustering techniques. The process involved preprocessing, feature engineering, applying KMeans clustering, and interpreting the output to label market states such as *Bullish High Volatility* or *Bearish Low Volume*.

---

## ✅ Key Tasks Completed

- ✔️ Feature extraction from order book & trade data  
- ✔️ Feature normalization & scaling  
- ✔️ Elbow method for optimal `k` value in clustering  
- ✔️ PCA for 2D visualization of clusters  
- ✔️ Heatmap to analyze cluster behavior  
- ✔️ Cluster labeling based on feature statistics  

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `features.csv` | Normalized features used for clustering |
| `elbow_plot.png` | Plot showing WCSS vs `k` for elbow method |
| `pca_plot.png` | 2D PCA projection of clusters |
| `cluster_heatmap.png` | Heatmap of average feature values per cluster |
| `regime_labels.csv` | Cluster-wise regime labels (e.g., “High Volatility Bullish”) |
| `notebook.ipynb` | Jupyter notebook with full code & explanations |

---

## 🧠 Insights

- Identified **3-5 stable regimes** with distinct patterns in price volatility, volume, and order book depth.
- PCA and heatmaps helped interpret cluster behavior effectively.
- Assigned intuitive regime labels for easy mapping to trading strategies.
  
---

## 📌 Notes

- All clustering was performed using **KMeans** with `sklearn`
- Features were extracted on **minute-level data**
- PCA and Seaborn used for visualization

---

