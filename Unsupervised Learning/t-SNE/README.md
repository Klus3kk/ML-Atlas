# t-Distributed Stochastic Neighbor Embedding (t-SNE)

## Overview
t-Distributed Stochastic Neighbor Embedding (t-SNE) is a non-linear dimensionality reduction technique particularly effective for visualizing high-dimensional data in 2D or 3D spaces. Unlike linear methods like PCA, t-SNE preserves the local structure of data, making it useful for visualizing complex patterns and clusters.

## Where is it Used?

- **Data Visualization**: Creating 2D or 3D representations of high-dimensional data for easier interpretation.
- **Clustering**: Visualizing inherent clusters in data.
- **Understanding Embeddings**: Visualizing word embeddings, neural network activations, etc.

## How Does it Work?

t-SNE minimizes the divergence between two distributions: one that measures pairwise similarities of the data points in the high-dimensional space, and one that measures the corresponding similarities in the low-dimensional space. This process is iterative and adjusts the positions of points in the lower-dimensional space to match the pairwise similarities from the original space.