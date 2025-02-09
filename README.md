# Comparative Performance Study of Clustering Algorithms

## Overview
This project explores the performance of different clustering algorithms on the UCI Iris dataset. It applies different preprocessing techniques, evaluates multiple clustering methods, and compares results using various performance metrics.

## Dataset
- **Source**: UCI Machine Learning Repository
- **Dataset Used**: Iris Dataset
- **Features**: Sepal length, sepal width, petal length, petal width
- **Classes**: Three species of iris flowers

## Preprocessing Techniques
- **StandardScaler**: Standardizes features by removing the mean and scaling to unit variance
- **MinMaxScaler**: Scales features to a fixed range (0,1)

## Clustering Algorithms Evaluated
1. **K-Means Clustering**
2. **DBSCAN (Density-Based Spatial Clustering)**
3. **Agglomerative Hierarchical Clustering**

## Performance Metrics Used
- **Silhouette Score**: Measures how similar a point is to its cluster compared to other clusters
- **Davies-Bouldin Index**: Evaluates intra-cluster similarity and inter-cluster differences
- **Calinski-Harabasz Score**: Measures dispersion between clusters

## Results & Visualizations
- **Comparison of clustering performance across different preprocessing techniques**
- **Bar charts showing metric scores for each algorithm**
- **PCA visualization of the clustered data**

## Files Included
- `clustering_comparison.ipynb`: Jupyter Notebook with complete analysis
- `clustering_comparison_results.csv`: Results from clustering evaluation

## How to Run the Code
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd clustering-comparison
   ```
2. Open `clustering_comparison.ipynb` in Google Colab or Jupyter Notebook
3. Run all cells to see clustering results and visualizations

## Conclusion
- Different preprocessing techniques affect clustering results significantly.
- K-Means generally performs well when clusters are well-separated.
- DBSCAN can detect outliers but is sensitive to parameter selection.
- Agglomerative Clustering performs similarly to K-Means in structured datasets.

## Author
This project was developed as part of a study on clustering algorithms. Contributions and feedback are welcome!

