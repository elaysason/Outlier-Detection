# Outlier-Detection
Utilizing PySpark for distributed data processing to perform outlier detection and clustering on a dataset containing bid request information related to online advertisements, using K-means and Bisecting K-means algorithms.
## Introduction

 The code is written in Python and uses PySpark for distributed data processing. The main goal of this project is to detect outliers in a dataset and perform clustering on the data using the K-means and Bisecting K-means algorithms. The dataset contains bid request information related to online advertisements.

## Getting Started

### Prerequisites

Before running the code, make sure you have the following:

1. Python installed on your system.
2. PySpark installed. You can install it using the following command:

```bash
pip install pyspark
```


## Instructions

1. Open the Jupyter Notebook file named "FinalProjectA_318170917_322995358.ipynb".
2. Execute the code cells step-by-step. The code is written with explanations at each stage.
3. The data preprocessing, feature engineering, and outlier detection process will be performed first.
4. After that, the K-means and Bisecting K-means clustering algorithms will be applied.
5. The results of clustering and outlier detection will be visualized.

## Code Explanation

The code can be divided into the following sections:

1. Data Preparation: The data is read from the JSON files and preprocessed to flatten nested JSON structures.
2. Feature Selection: The relevant features for clustering and outlier detection are chosen.
3. One-Hot Encoding: Categorical features are one-hot encoded to be used in the clustering process.
4. Feature Scaling: The selected features are scaled using StandardScaler for better performance in clustering algorithms.
5. K-means Clustering: K-means algorithm is applied to cluster the data into different groups.
6. Bisecting K-means Clustering: Bisecting K-means algorithm is applied to compare clustering results with K-means.
7. Outlier Detection: Outliers are detected based on the distance from the closest centroid.
8. Results Visualization: The results of clustering and outlier detection are visualized using PCA.

## Results

The project provides two main results:

1. Clustering Results: The data is clustered into multiple groups using K-means and Bisecting K-means algorithms. The results are visualized using PCA to show the clusters in a 2D space.

2. Outlier Detection Results: Outliers are detected based on the distance of data points from the closest centroid. The outliers are identified and visualized.

