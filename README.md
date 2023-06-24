# ClusterLens
Utility Library to Analyze Clusters

### What would be useful in analyzing cluster results
1. Visualization (in case of non-hierarchical results) - Viz using PCA TSNE UMAP, Heatmap for 3 features (continous/discrete), dendrogram for hierarchical clustering
2. If Data is text - Top Terms (either based on logistic regression or chi-square approach (1 vs all approach))
3. Inter vs Intra similarity
4. Feature Stats per cluster
5. Median / Center Analysis
6. Feature Importance: Identifying the key features or variables that contribute the most to the separation or formation of clusters.
7. In Summary :
  * Cluster Validation
  * Visualization
  * Centroid Analysis
  * Text Clustering Utils
    * Top Frequency Terms (Tf-idf based, ngram optional, min_df,max_df)
    * Filter for stopwords
    * Tokenization
    * replace emoji with text (demoji)
8. decorator - to record results
9. Pipeline - to do all the above in sequence
10. Unit testing
