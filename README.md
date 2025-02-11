# 📊 **Title: Grouping Customers to Maximize Campaign Effectiveness**

# **Authors: Nikolaos Marakis, Maria Kopsacheili, Apostolis Karapatis**

## 📌 **Project Overview** 

A Data-Driven Approach to Identify the different customers profiles.

This project employs a data-driven approach to identify distinct customer profiles. The marketing department tasked our data science team with segmenting customers based on their characteristics and behaviors. The goal is to determine the unique traits of each customer segment, enabling the marketing team to design highly targeted campaigns for each group.

# 🎯 **Objectives**

- Data Cleaning: Remove missing values, handle outliers, and normalize numerical features to prepare the data for machine learning.

- Exploratory Data Analysis (EDA): Investigate relationships between spending habits, demographics, and income levels. Visualize distributions and correlations to inform feature selection.

- Model Training: Implement clustering models for customer segmentation using K-Means, Kmedoids, DBSCAN, Hierarchical Clustering (Agglomerative), PCA, focusing on attributes such as income, number of children, age, marital status, product engagement, and education. 

- Model Evaluation: Assess the performance of the chosen clustering model to ensure it effectively identifies well-defined customer groups. For the evaluation we used Silhouette Score and Elbow method.

# 🛠️ **Technologies used**

- Pandas: Utilized for data preprocessing and analysis.
- Matplotlib, Seaborn: Employed for creating informative data visualizations.
- Scikit-Learn: Used to develop the K-Means clustering model.

# ✅ **Results**

We concluded that our best option was Kmeans with k=3. So, the clustering analysis revealed three distinct customer segments:
- Cluster 0: Low-income families with small children.
- Cluster 1: Medium-income families with teenagers.
- Cluster 2: High-spending individuals without children, showing a significantly higher response rate to targeted campaigns.

# 💰 **Campaign Strategy Recommendations**

- Current Strategy: Generic campaigns with low conversion rates.
- Refined Strategy: Implement cluster-focused campaigns tailored to each customer profile to improve response rates, increase loyalty, and maximize revenue.

# 🚀 **Next Steps**

- Marketing Team: Evaluate the performance of targeted marketing campaigns for each cluster.
- Data Science Team: Monitor campaign performance and refine customer segmentation as needed.
