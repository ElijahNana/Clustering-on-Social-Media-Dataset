# Clustering-on-Social-Media-Dataset

- This project explores user segmentation using clustering algorithms applied to a social media user interaction dataset. By clustering based on behaviour metrics like likes, comments, and messages sent per day, we aim to uncover hidden patterns in user engagement.

---

Dataset Overview

- Features include: `Likes`, `Comments`, `Average Messages Sent/ Day`, etc.
- Goal: Group users into behaviour-based segments using unsupervised learning
- All null values handled appropriately using statistical imputation methods (mean/mode)

---

Objectives

- Clean and prepare a social media dataset for clustering
- Use visualisations to explore feature distributions and relationships
- Apply KMeans, Hierarchical Clustering and DBSCAN
-Use the Elbow Method to determine optimal k
- Compare results from different clustering approaches

---

Tools & Libraries

- Python (Jupyter Notebook)
- pandas, seaborn, matplotlib
- scikit-learn (KMeans, DBSCAN, metrics)
- scipy (for hierarchical clustering)

---

Clustering Techniques Applied

KMeans Clustering

- Used Elbow Method to justify `k=3`
- Cluster labels added to the dataset for further interpretation

Hierarchical Clustering

- Applied Ward linkage
- Visualised with a dendrogram

DBSCAN

- Detected dense clusters and outliers
- Used Davies-Bouldin Index to evaluate cluster separation

---

Visualisations Included

- Countplots and Bar plots
- Boxplots for detecting outliers
- Elbow Method plot to support KMeans clustering
- Cluster visualisations for all 3 models

---

Key Insights

- KMeans performed well with `Likes` and `Comments` as features
- DBSCAN identified noise points and low-engagement users
- Hierarchical clustering revealed nested structure in user similarity

