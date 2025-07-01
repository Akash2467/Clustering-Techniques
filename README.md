# Clustering-Techniques

This project demonstrates various unsupervised learning techniques using the classic Iris dataset. It explores how different clustering algorithms group data without labels and evaluates the effectiveness using Silhouette Scores, visualizations, and cluster-level statistics.
---
## Dataset
- **Source**: Iris Dataset (UCI Machine Learning Repository)
- **Features**:
  - SepalLength
  - SepalWidth
  - PetalLength
  - PetalWidth

---

## Clustering Algorithms Implemented

### 1. K-Means Clustering
- Optimal number of clusters identified using the Elbow Method
- Evaluated using Silhouette Score
- Visualized using 2D scatter plot

### 2. Agglomerative Hierarchical Clustering
- Dendrogram used to visualize the hierarchical structure
- Ward linkage with Euclidean distance
- Evaluated using Silhouette Score

### 3. DBSCAN
- Density-based clustering method
- Automatically detects noise and outliers
- Epsilon selected using the K-distance graph
- Silhouette Score computed (excluding noise points)

---

## Evaluation Metrics and Visualizations

- Silhouette Scores for all clustering methods
- Cluster-wise mean statistics of features
- Visualizations:
  - Elbow Plot for K-Means
  - Dendrogram for Agglomerative Clustering
  - K-Distance Graph for DBSCAN
  - 2D scatter plots showing clustering results

---

## Technologies Used

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- scipy

---
