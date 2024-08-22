# DBSCAN

## Overview
DBSCAN is a density-based clustering algorithm that groups together points that are closely packed, marking points that lie alone in low-density regions as outliers. Unlike k-Means, it does not require the number of clusters to be specified beforehand.

### Where is it Used?
- **Geospatial data analysis:** Identifying hotspots or clusters in spatial data.
- **Anomaly detection:** Detecting outliers in financial data.
- **Image segmentation:** Identifying connected regions in images.

## How Does it Work?
DBSCAN works by identifying dense regions in the data as clusters, defined by a minimum number of points within a given distance (epsilon). Points that don't meet the density criteria are considered noise or outliers.
