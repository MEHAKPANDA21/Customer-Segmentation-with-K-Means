Customer Segmentation with K-Means

This project applies K-Means clustering to segment customers based on their Annual Income and Spending Score. The dataset used is the popular Mall Customers dataset.

📊 Project Overview

The goal is to group customers into clusters with similar spending behaviors.

This helps businesses understand customer segments and design targeted marketing strategies.

🧾 Dataset

The dataset Mall_Customers.csv contains:

CustomerID – Unique ID assigned to each customer

Gender – Male/Female

Age – Age of the customer

Annual Income (k$) – Income in thousands of dollars

Spending Score (1–100) – Score assigned based on customer spending behavior

👉 In this notebook, only Annual Income (k$) and Spending Score (1–100) are used as features for clustering.

⚙️ Steps in the Notebook

Import libraries and load dataset

Explore dataset (shape, info, missing values)

Select features: Annual Income & Spending Score

Use the Elbow Method to find the optimal number of clusters

Apply K-Means clustering

Visualize customer segments with scatter plots

📈 Output

The model predicts cluster labels (customer segments).
Each customer is assigned to a group such as:

High income, high spending

High income, low spending

Low income, high spending

Low income, low spending

📌 Requirements

Python 3.x

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn
