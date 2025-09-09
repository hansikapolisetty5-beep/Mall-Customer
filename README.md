# 🧠 Customer Segmentation using DBSCAN

## 📊 Dataset Overview

This project analyzes customer behavior using unsupervised learning. The dataset contains the following columns:

| Column Name              | Description                                           |
|--------------------------|-------------------------------------------------------|
| `CustomerID`             | Unique identifier for each customer                  |
| `Gender`                 | Gender of the customer                               |
| `Age`                    | Age of the customer                                  |
| `Annual Income (k$)`     | Annual income in thousands of dollars                |
| `Spending Score (1-100)` | Score assigned by the mall based on spending habits  |

## 🎯 Objective

Apply **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to identify meaningful customer segments without predefining the number of clusters.

## ⚙️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📌 Workflow

1. **Data Preprocessing**
   - Encoding categorical variables
   - Feature scaling
   - Handling missing values

2. **Exploratory Data Analysis**
   - Distribution plots
   - Correlation heatmaps
   - Pair plots

3. **DBSCAN Clustering**
   - Parameter tuning (`eps`, `min_samples`)
   - Cluster visualization
   - Outlier detection

4. **Insights & Recommendations**
   - Segment profiling
   - Business strategy suggestions

## 📈 Results

- DBSCAN identified distinct clusters and noise points.
- High-income low-spending customers were flagged for targeted marketing.
- Outliers revealed unique spending behaviors worth further analysis.


