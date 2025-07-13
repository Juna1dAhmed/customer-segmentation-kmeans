
#  Customer Segmentation using K-Means Clustering

This project performs customer segmentation on the **Online Shoppers Intention** dataset using **K-Means Clustering**. The goal is to identify distinct customer groups based on session behavior, such as time spent, bounce rate, and page interaction.

---

## 📂 Project Structure

```
customer-segmentation-kmeans/
├── customer_segmentation.ipynb       # Main notebook with all code and visualizations
├── online_shoppers_intention.csv     # Dataset 
├── segmented_customers.csv           # Output data with cluster labels
├── requirements.txt                  # Python dependencies
└── README.md                         # This file
```

---

## 📌 Dataset Overview

- **Name:** Online Shoppers Intention
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)
- **Records:** 12,330 sessions
- **Features:** Includes administrative, informational, product-related pages, bounce/exit rates, page values, month, operating system, region, traffic type, visitor type, weekend flag, and revenue.

---

## 🔧 Techniques Used

- ✅ Data Preprocessing & Cleaning
- ✅ Feature Encoding (Categorical to Numeric)
- ✅ Feature Scaling with `StandardScaler`
- ✅ Clustering with `KMeans` (using Elbow + Silhouette)
- ✅ Dimensionality Reduction with `PCA`
- ✅ Visualization using `Seaborn` and `Matplotlib`
- ✅ Cluster Summary, Boxplots, Pairplots, and Heatmaps

---

## 📊 Outputs & Visualizations

- **Elbow Plot**: To find the optimal number of clusters
- **Silhouette Score Plot**: To evaluate cluster separation
- **PCA Plot**: 2D cluster visualization
- **Heatmaps**: Average feature values per cluster
- **Boxplots & Pairplots**: Deep behavioral insights

---


## 📦 Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

Install with:
```bash
pip install -r requirements.txt
```

---

## ✨ Credits

- Dataset: UCI Machine Learning Repository
- Developed by: [Junaid Ahmed](https://github.com/Juna1dAhmed)
