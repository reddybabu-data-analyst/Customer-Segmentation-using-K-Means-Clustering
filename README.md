# Customer Segmentation using Machine Learning

## Project Overview

Customer segmentation is an important technique used by businesses to understand different groups of customers based on their purchasing behavior.

In this project, we apply **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on **Annual Income** and **Spending Score**.

The objective is to identify distinct customer groups that can help businesses design **targeted marketing strategies** and improve customer engagement.

---

## Problem Statement

Businesses often have a large number of customers with different purchasing habits. Without segmentation, it is difficult to understand customer behavior and create effective marketing campaigns.

This project aims to:

* Analyze customer data
* Identify hidden patterns
* Group customers into meaningful segments

---

## Dataset

Dataset used: **Mall Customer Segmentation Dataset**

Features included:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

The **Spending Score** is assigned by the mall based on customer purchasing behavior.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Algorithm

**K-Means Clustering**

K-Means is an unsupervised learning algorithm that groups data points into clusters based on similarity.

Steps involved:

1. Choose number of clusters (K)
2. Assign data points to nearest centroid
3. Recalculate centroids
4. Repeat until clusters stabilize

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Feature Scaling
6. Finding Optimal Clusters using Elbow Method
7. Applying K-Means Clustering
8. Cluster Visualization
9. Business Insights

---

## Data Visualization

The clusters are visualized using scatter plots showing customer groups based on **Annual Income** and **Spending Score**.

This helps clearly identify different customer segments.

---

## Customer Segments Identified

Cluster 1: **High Income – High Spending**
Premium customers who generate high revenue.

Cluster 2: **High Income – Low Spending**
Potential customers who can be targeted with marketing campaigns.

Cluster 3: **Low Income – High Spending**
Impulsive buyers who respond well to promotions.

Cluster 4: **Low Income – Low Spending**
Budget-conscious customers.

Cluster 5: **Average Income – Average Spending**
Regular customers with moderate purchasing behavior.

---

## Business Insights

Customer segmentation helps businesses:

* Identify high-value customers
* Design personalized marketing strategies
* Improve customer retention
* Increase sales and profitability

---

## Project Structure

project-folder
│
├── data
│   └── Mall_Customers.csv
│
├── notebooks
│   └── customer_segmentation.ipynb
│
├── images
│   └── cluster_visualization.png
│
├── requirements.txt
│
└── README.md

---

## How to Run the Project

1. Clone the repository

2. Install required libraries

pip install -r requirements.txt

3. Run the Jupyter Notebook

jupyter notebook

---

## Future Improvements

* Add more features such as customer purchase history
* Try other clustering algorithms (DBSCAN, Hierarchical Clustering)
* Build an interactive dashboard using **Streamlit**

---

## Author

pavani

If you like this project, feel free to ⭐ the repository.
