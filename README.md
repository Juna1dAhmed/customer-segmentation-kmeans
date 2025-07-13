
# 🧠 Customer Segmentation using K-Means Clustering

This project performs customer segmentation on the **Online Shoppers Intention** dataset using **K-Means Clustering**. The goal is to identify distinct customer groups based on session behavior, such as time spent, bounce rate, and page interaction.

---

## 📂 Project Structure

```
customer-segmentation-kmeans/
├── customer_segmentation.ipynb       # Main notebook with all code and visualizations
├── online_shoppers_intention.csv     # Dataset (optional to include in repo)
├── segmented_customers.csv           # Output data with cluster labels
├── kmeans_model.pkl                  # Saved KMeans model (optional)
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

## 💾 Files Generated

- `segmented_customers.csv` – Dataset with cluster labels
- `kmeans_model.pkl` – Saved clustering model (optional)

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Juna1dAhmed/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   - Open `customer_segmentation.ipynb` in **Jupyter** or **Google Colab**
   - Follow the steps in the notebook to upload the dataset and run the code

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
