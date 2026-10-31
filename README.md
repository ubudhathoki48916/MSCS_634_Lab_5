# MSCS 634 Lab 5: Hierarchical and DBSCAN Clustering

## Purpose

The objective of this lab is to perform Hierarchical Clustering and DBSCAN on the Wine Dataset using the scikit-learn package. This lab covers data preprocessing, clustering, visualization, and evaluation.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Lab Activities

1. Loaded and explored the Wine dataset.
2. Explored the dataset using Pandas functions.
3. The dataset was standardized using StandardScaler.
4. The Agglomerative Hierarchical Clustering algorithm was applied.
5. Scatter Plots and a dendrogram were created.
6. DBSCAN was used with different eps and min_samples values.
7. Silhouette Score, Homogeneity Score, and Completeness Score calculated.
8. Comparison between the two clustering algorithms was made.

## Key Insights

Hierarchical clustering was used to examine how the observations related to one another and how the clusters formed.

DBSCAN demonstrated how density-based clustering works by forming clusters and identifying noise points. The DBSCAN results depended on the values chosen for eps and min_samples.

The evaluation measures were useful in comparing the quality of the clusters.

## Challenges and Decisions

Another challenge included the choice of appropriate clustering parameters. It was essential to standardize the Wine dataset since its attributes differ in scale.

It was necessary to check different parameter combinations to see how results may vary.

## Conclusion

The experiment gave me hands-on knowledge about unsupervised learning methods. My knowledge about hierarchical clustering, density-based clustering, normalization, visualization, and evaluation techniques was enhanced by this experiment.