# Hierarchical Clustering

## Overview
Hierarchical Clustering builds a hierarchy of clusters by either merging small clusters into larger ones (agglomerative) or splitting large clusters into smaller ones (divisive). It is often visualized using dendrograms.

### Where is it Used?
- **Gene expression data analysis:** Grouping similar genes or samples.
- **Social network analysis:** Identifying communities within networks.
- **Document classification:** Organizing documents into a hierarchy of topics.

## How Does it Work?
Hierarchical clustering creates clusters that form a tree-like structure (dendrogram). The agglomerative approach starts with each data point as its own cluster and merges the closest pairs of clusters iteratively until only one cluster remains.
