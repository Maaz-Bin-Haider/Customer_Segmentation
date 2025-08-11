# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering** to segment customers into distinct groups based on their **Age**, **Annual Income**, and **Spending Score**.  
The goal is to help businesses identify target customer groups and personalize marketing strategies.

Dataset used: [Mall Customers Dataset - Kaggle](https://www.kaggle.com/datasets)

---

## 📂 Steps Performed

### 1️⃣ Data Loading & Exploration
- Imported the dataset and explored its structure.
- Visualized initial relationships between features.

### 2️⃣ Data Visualization
- Scatter plots to observe trends between features.
- Pair plots for multi-feature relationships.

### 3️⃣ Data Scaling
- Applied **StandardScaler** to normalize feature values.
- Visualized data before and after scaling using:
  - Scatter plots

### 4️⃣ Finding Optimal Clusters
- Used **Elbow Method** by plotting **SSE (Sum of Squared Errors)** vs. number of clusters.
- Identified the optimal number of clusters for K-Means.

### 5️⃣ Applying K-Means Algorithm
- Implemented **K-Means** with the chosen number of clusters.
- Assigned each customer a cluster label.

### 6️⃣ Cluster Visualization
- 2D Scatter Plot: Age vs Spending Score

---

## 📊 Results
- Customers were segmented into meaningful groups.
- Visualization clearly shows different spending and income patterns across clusters.
- The model can help businesses target specific customer profiles.

---

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---
