# Singular Value Decomposition (SVD)

## Overview
Singular Value Decomposition (SVD) is a matrix factorization technique that decomposes a matrix into three component matrices. It’s widely used in dimensionality reduction, data compression, and noise reduction.

### Where is it Used?
- **Dimensionality Reduction:** Reducing the number of features while retaining the essential information.
- **Data Compression:** Compressing data for storage and transmission.
- **Latent Semantic Analysis (LSA):** Finding relationships between terms and documents in text data.

## How Does it Work?
SVD decomposes a matrix \( A \) into three matrices \( U \), \( Σ \), and \( V^T \), where:
- \( U \) and \( V^T \) are orthogonal matrices.
- \( Σ \) is a diagonal matrix containing the singular values, representing the importance of each component.

The data can be approximated by projecting it onto these components, reducing its dimensions while retaining significant features.
