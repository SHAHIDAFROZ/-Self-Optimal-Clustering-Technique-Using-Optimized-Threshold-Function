# Self optimal clustering Algorithm Implementation

## Overview

Self-optimization clustering is a technique used in data analysis to automatically determine the optimal number of clusters within a dataset without prior knowledge of the dataset's structure. This method iteratively adjusts and fine-tunes the clustering process by evaluating various metrics, such as intra-cluster variance and inter-cluster distance, to find a balance that minimizes within-cluster differences while maximizing separation between clusters. By incorporating feedback mechanisms, self-optimization clustering continuously refines the clusters until a stable, optimal solution is achieved. This approach is particularly valuable in scenarios where the natural grouping of data is not evident, making it a powerful tool for uncovering hidden patterns and structures within complex datasets.

## Files

- `clustering_algorithm.py`: The main Python script that performs the clustering, computes metrics, and generates plots.

## Requirements

To run the script, you need the following Python libraries:

- `numpy`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install numpy matplotlib
