# Overview
This Jupyter Notebook performs customer segmentation using clustering techniques based on purchasing behavior. 
The dataset used is Mall_Customers.csv, which contains customer information including CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).

#  Steps Performed
# 1. Data Loading and Exploration
Imported necessary libraries (pandas).
Loaded the dataset and displayed the first few rows to understand its structure.
# 2. Data Preprocessing
Selected relevant features for clustering: Age, Annual Income (k$), and Spending Score (1-100).
Normalized the data using StandardScaler to ensure all features contribute equally to the clustering process.
# 3. Determining Optimal Number of Clusters
Applied the Elbow Method using K-Means clustering to find the optimal number of clusters (k).
Plotted the inertia (within-cluster sum of squares) against the number of clusters to identify the "elbow point," which suggests the optimal k.
# 4. Applying K-Means Clustering
Chose k=4 based on the Elbow Method.
Applied K-Means clustering to the normalized data and predicted cluster labels.
# 5. Visualizing Clusters
Used Principal Component Analysis (PCA) to reduce the dimensionality of the data to 3 components for visualization.
Plotted the clusters in a 2D space using the first two principal components to visualize the customer segments.
# Results
The clustering analysis successfully segmented customers into 4 distinct groups based on their Age, Annual Income, and Spending Score. The visualization provides insights into the distribution and characteristics of each cluster.
# Requirements
Python 3.x
Libraries: pandas, scikit-learn, matplotlib
# Usage
Ensure the dataset Mall_Customers.csv is in the specified path.
Run the notebook cells sequentially to perform the clustering analysis.
Adjust the number of clusters or features as needed for different analyses.
# Conclusion
This analysis helps in understanding customer behavior and can be used for targeted marketing strategies, personalized recommendations, and improving customer engagement based on the identified segments.
