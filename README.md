### Crypto Clustering Project
## Overview
This project applies K-Means clustering to analyze and group cryptocurrencies based on their market performance. It also compares clustering results before and after PCA (Principal Component Analysis) to assess the impact of dimensionality reduction.

## Key Objectives
✔ Preprocess crypto market data
✔ Standardize features using StandardScaler
✔ Apply PCA to reduce dimensionality
✔ Use K-Means to cluster cryptocurrencies
✔ Compare Elbow Curve and Cluster distributions
✔ Visualize results using Matplotlib

## Data Preprocessing
The dataset (crypto_market_data.csv) contains percentage price changes over different time frames.
Data is standardized using StandardScaler() before clustering.
PCA is applied to reduce the number of features while retaining key variance.

## Clustering Analysis
# 1. Elbow Curve Analysis
Determines the optimal number of clusters (k) by plotting inertia values.
Compared for both original data and PCA-transformed data.
# 2. K-Means Clustering
Clusters are created using the best k-value determined from the Elbow Curve.
Clustering is performed on both original features and PCA-reduced features.
# 3. Visualization
Elbow Curve Comparison: Plots inertia vs. k-values to identify the optimal number of clusters.
Cluster Comparison: Side-by-side plots contrast clustering before and after PCA.

## Key Findings
✅ PCA reduces dimensionality, making K-Means more efficient.
✅ Clusters are clearer and better separated in PCA-transformed data.
✅ Fewer features improve computational efficiency without significant loss of information.
✅ Optimal k-value was determined using the Elbow Method.

