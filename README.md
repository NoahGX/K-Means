# K-Means Clustering

## Overview
The purpose of this Jupyter Notebook is to demonstrate the implementation of the k-means clustering algorithm on a synthetic dataset. It explores the algorithm's capability to segment data into clusters and analyzes the impact of outliers on clustering performance.

## Features
  - Implementation of k-means clustering.
  - Visualization of clustering results.
  - Analysis of the effect of outliers on clustering.
  - Experimentation with different numbers of clusters.

## Usage
To use this notebook, run each cell sequentially to see the implementation of the k-means algorithm, the creation of clusters, and the analysis of the results.

## Prerequisites
  - Python 3.x
  - Jupyter Notebook
  - Libraries: NumPy, Matplotlib, Scikit-learn

## Input
The notebook generates a synthetic dataset using Scikit-learn's `make_blobs` function. This dataset is then used to demonstrate the clustering.

## Output
The outputs are visualizations of the data points colored according to the cluster they belong to. It also displays plots showing the sensitivity of the algorithm to outliers and the separation between different clusters.

## Notes
  - The k-means algorithm's performance can significantly vary with the presence of outliers.
  - This notebook is intended for educational purposes to understand the basic workings and limitations of the k-means clustering algorithm.
