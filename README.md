Spotify Data Analysis

Analyze 100,000+ Spotify tracks to find natural groupings and insights. This project uses unsupervised learning (K-means, DBSCAN, Agglomerative Clustering) and dimensionality reduction (PCA, t-SNE).

Overview • Goal: Find hidden patterns in song features and identify how they cluster. • Techniques: • Data cleaning and scaling • Exploratory Data Analysis (EDA) • PCA for dimensionality reduction • K-means, DBSCAN, and Agglomerative Clustering • Evaluation with Silhouette, Calinski-Harabasz, Davies-Bouldin scores • t-SNE visualization

Project Structure
```
.
├── eda/                        # Plots and figures generated
├── dataset.csv                 # Spotify dataset
├── unsupervised_models.py     # Main pipeline code
└── README.md
```

Key Insights • Feature distributions vary (some near-normal, some heavily skewed). • PCA shows 7 components explain ~90% variance. • K-Means finds about 8 clusters (based on metrics). • DBSCAN is sensitive to hyperparameters and often yields fewer insights. • Agglomerative clustering and t-SNE help reveal distinct groups.

Future Directions • Incorporate genre encoding for finer analysis. • Improve hyperparameter tuning with automated methods. • Use domain expertise to interpret clusters and possibly build a recommendation system.
