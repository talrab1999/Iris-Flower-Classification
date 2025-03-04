# Iris Flower Clustering

## Overview

This project performs **unsupervised clustering** on the Iris dataset to group flowers into three species using different models. 
The goal is to evaluate how well clustering techniques can separate species without labeled training data.

## Dataset

The dataset (`Iris.csv`) contains **150 samples** with the following features:

- **SepalLengthCm**
- **SepalWidthCm**
- **PetalLengthCm**
- **PetalWidthCm**
- **Species** (used only for evaluation, not in clustering)

## Approach

1. **Data Preprocessing:**

 - Load the dataset.
 - Extract feature columns for clustering.
 - Keep `Species` separately for evaluation.

2. **Clustering Methods Tried:**

 - **K-Means**
 - **PCA + K-Means
 - **Hierarchical Clustering**
 - **Gaussian Mixture Model (GMM)** (Best result: **97% accuracy**)

3. **Evaluation:**

 - Map predicted clusters to actual species, to check the accuracy.
 - Visualize results using **scatter plots**.

## Results

- **GMM achieved 97% accuracy**, outperforming K-Means.
- **Visualization:** Clustering results were compared to true species labels using `seaborn` scatter plots.


## Technologies

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib


