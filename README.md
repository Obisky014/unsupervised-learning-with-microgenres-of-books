# Clustering Book Genres from Amazon Top 100 Trending Dataset

## Overview

This project uses unsupervised learning to group books into clusters based on text features from a real dataset of Amazon's Top 100 Trending Books. It also builds upon earlier experiments with two generated datasets used to grasp the basics of unsupervised learning and cluster visualization.

## Dataset Summary

The dataset includes:

* Book Title
* Author
* Genre
* Price
* Rating
* Year
* Rank
* URL

There was no description column, so a new column was created by combining the book title and genre to use as input text.

## Main Steps

1. **Text Feature Creation**: Combined book title and genre to form a text column.
2. **TF-IDF Vectorization**: Transformed the text column into numerical vectors.
3. **Clustering**: Used KMeans clustering to group books by text similarity.
4. **Dimensionality Reduction**: Applied PCA to reduce features to 2D for visualization.
5. **Cluster Labeling**: Labeled clusters based on the most common genre within each.
6. **Visualization**: Plotted the clusters and made layout tweaks to fix issues like annotation errors and legend positioning.

## Key Learnings

* Meaningful clustering can still be achieved with limited text data.
* Genre can serve as a basic stand-in for more specific microgenre labeling.
* Visualization often requires troubleshooting and layout adjustment.

## Future Ideas

* Enrich data with book descriptions using external sources.
* Explore other clustering or dimensionality reduction methods.

This project helped reinforce unsupervised learning concepts while facing and solving common real-world data and visualization challenges.
