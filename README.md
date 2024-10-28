# Customer-Analysis---Clustering
# Project Overview
This project aims to perform customer segmentation using unsupervised learning techniques. By analyzing customer behavior and demographics, we identified patterns that allow for a deeper understanding of customer groups and targeted strategies. We used K-Means and DBSCAN clustering methods to classify the customers and employed Principal Component Analysis (PCA) to reduce dimensionality and improve the efficiency of our clustering algorithms. The analysis revealed four distinct customer clusters, each with unique characteristics.

# Methods
1. Data Preprocessing
Cleaning and Transformation: The data underwent standard preprocessing steps, including handling missing values, scaling features, and encoding categorical variables as needed.
Dimensionality Reduction (PCA): Principal Component Analysis (PCA) was used to reduce the feature space, improving clustering accuracy and reducing computational load. This also allowed for easier visualization of the customer clusters.
2. Clustering Techniques
K-Means Clustering: We used the K-Means algorithm as our primary method, iterating through various values of k to determine the optimal number of clusters. After analyzing the elbow plot and silhouette score, we found that four clusters best represented the data.
DBSCAN Clustering: Density-Based Spatial Clustering of Applications with Noise (DBSCAN) was applied to find clusters based on density. DBSCAN allowed for the detection of outliers that do not fit into any primary cluster, further refining our K-Means results.
# Results
The analysis resulted in four main clusters, each representing a distinct type of customer group. Here’s a brief overview:

1. Cluster 0: Older parents with teenagers, often single, with 2-4 members per family.
2. Cluster 1: Couples or individuals without children, with high income, typically spanning all age groups.
3. Cluster 2: Younger parents, usually with one child and smaller family sizes (up to 3 members).
4. Cluster 3: Older, lower-income parents with 2-5 family members, usually with teenagers.

Each cluster shows unique behavioral and demographic patterns, allowing for potential targeted marketing strategies and personalized customer engagement.

# Files
notebook.ipynb: Contains all steps in the analysis, including data preprocessing, PCA, and the K-Means and DBSCAN implementations.
data: https://creativecommons.org/publicdomain/zero/1.0/
README.md: Documentation of the project (this file).

# Future Work
Further Feature Engineering: Incorporating additional data points (such as purchase history or customer feedback) could lead to more refined clusters.
Experimenting with Other Clustering Algorithms: Trying algorithms like Agglomerative Clustering may reveal additional insights.
Cluster Profiling for Targeted Marketing: Using these customer segments for targeted marketing campaigns could validate the practical impact of our analysis.
# Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
