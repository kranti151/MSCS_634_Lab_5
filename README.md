# MSCS_634_Lab_5  
### Clustering Techniques using Hierarchical and DBSCAN Algorithms

---

## Overview
This lab applies Agglomerative Hierarchical Clustering and DBSCAN to the Wine dataset from the `sklearn` library. The goal is to understand clustering techniques, tune parameters, evaluate results using clustering metrics, and visually interpret how data groups are formed. All steps were completed using a Jupyter Notebook environment.

---

## Objectives
- Load and explore the Wine dataset  
- Standardize dataset features  
- Apply Hierarchical Clustering (Agglomerative) and DBSCAN  
- Visualize clusters using PCA-based scatter plots  
- Generate and interpret a dendrogram  
- Calculate clustering evaluation metrics:
  - Silhouette Score  
  - Homogeneity Score  
  - Completeness Score  
- Compare both clustering algorithms and reflect on their strengths and weaknesses

---

## Key Insights
- **Hierarchical Clustering** worked best with 3 clusters, producing clear separation. The dendrogram helped understand cluster merging at each level.
- **DBSCAN results were highly dependent on `eps` and `min_samples`.** Lower values detected more noise, larger values resulted in fewer but less distinct clusters.
- **Hierarchical Clustering performed better overall in terms of structure and consistency**, while **DBSCAN was more effective at detecting outliers.**
- **PCA was used only to visualize clusters**, not for clustering itself.

---

## Challenges Faced
- Tuning DBSCAN parameters required experimentation.
- Selecting the correct number of clusters for Hierarchical Clustering required dendrogram observation.
- Visualizing multi-dimensional data required reducing dimensions using PCA.
- Ensuring proper feature scaling before clustering was essential.
