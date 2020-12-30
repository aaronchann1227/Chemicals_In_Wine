# Chemicals in Wine

## Purpose
Use unsupervised learning and clustering algorithms to
  
- Understand and explore the chemical properties of potential groups of wines variants.
- Understand and explore chemical components that best describe the red and white wine variants.

## Algorithms and methods used
- K-means
- Fuzzy C-means
- Non Negative Matrix(NMF)
- T-SNE plot
- Silhouette plot

## Metrics used
- Average Silhouette Score
- Adjusted Rand Index	
- Completeness Score	
- Homogeneity Score

## Findings
##### *Discovered a grouping with 4 underlying clusters of wine, and they are all with different characteristics:*
**Cluster 0:**
- Highest concentration of residual sugar and both the free and the total sulfur dioxide.
- Lowest alcohol level.

**Cluster 1:**
- Highest quality wine and highest concentration of alcohol.
- Lowest density. 

**Cluster 2:**
- Highest pH and the highest concentration of fixed acidity, volatile acidity, chlorides, and sulphate.
- Lowest free and total sulfur dioxide.

**Cluster 3:**
- characterized by low density and low chlorides.

##### *Identified the red/white wine clusters and here are their respective characteristics:*

**Cluster 0(Red):**
- High "acidity" and "sulphate" concentration, low "total sulfur dioxide" and "free sulfur dioxide" concentration.


**Cluster 1(White):**
- High "residual sugar", low "sulphate", "pH", "density", "chlorides", and "acidity" concentration. 
