# Heart Disease Clustering - Unsupervised Learning

## Project III: Unsupervised Machine Learning

###  Student Information
**Name:** Ayesha Sumbal
**Course:** Introduction to Machine Learning
**Submission Date:** June 10, 2026
**GitHub:** [sumbal00001234-jpg/ML-HeartDisease-Clustering]

## Assignment-III / Project-III

---

##  Project Overview
This project applies **3 unsupervised clustering algorithms** to discover natural patient groupings in the Heart Disease dataset without using labels.


---

##  Algorithms Implemented

| # | Algorithm | Type | Key Feature |
|---|-----------|------|-------------|
| 1 | **K-Means** | Partitional | Fast, spherical clusters |
| 2 | **Hierarchical** | Tree-based | Dendrogram visualization |
| 3 | **DBSCAN** | Density-based | Noise detection, irregular shapes |

---

##  Results

| Algorithm | Silhouette Score | Time (sec) | Clusters | Noise |
|-----------|-----------------|------------|----------|-------|
| K-Means | 0.1247 | 0.080 | 3 | 0 |
| **Hierarchical** | **0.1533** | **0.058** | **3** | **0** |
| DBSCAN | -1 | 0.170 | 1 | 47 |

**Best Algorithm:** Hierarchical Clustering (Highest silhouette score: 0.1533)

---

##  Interpretation

### K-Means (Silhouette: 0.1247)
- Found 3 distinct patient groups
- Silhouette score indicates moderate cluster separation
- Fastest execution time

### Hierarchical Clustering (Silhouette: 0.1533)  BEST
- Highest silhouette score among all algorithms
- Also found 3 natural clusters
- Very fast (0.058 seconds)
- Dendrogram shows clear hierarchy

### DBSCAN (Silhouette: -1)
- Only found 1 cluster plus 47 noise points
- This is expected - DBSCAN works differently
- Noise points represent unique/outlier patients

---
