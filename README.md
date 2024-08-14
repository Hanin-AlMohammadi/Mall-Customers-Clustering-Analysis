# mall-customers-clustering-analysis
This project involves clustering analysis on the "Mall_Customers" dataset using various algorithms, including K-Means, DBSCAN, and Agglomerative Clustering. The objective is to segment customers based on features like annual income, spending score, and gender, and to evaluate the performance of each clustering method using the Silhouette Score. 

# Mall Customers Clustering Analysis

## Overview

This project focuses on clustering analysis of the "Mall_Customers" dataset using three different clustering algorithms:

- **K-Means**
- **DBSCAN**
- **Agglomerative Clustering**

The goal is to identify distinct customer segments based on their annual income, spending score, and gender. We evaluate the performance of each algorithm using the Silhouette Score and provide visualizations of the clustering results.

## Dataset

The dataset used in this project is the "Mall_Customers.csv" file, which contains the following features:

- **Gender**: Categorical (Male/Female)
- **Age**: Numeric
- **Annual Income (k$)**: Numeric
- **Spending Score (1-100)**: Numeric

## Project Structure

- **Data Preprocessing:** Convert categorical values to numerical values, explore the dataset.
- **Clustering Models:** Apply K-Means, DBSCAN, and Agglomerative Clustering on selected features.
- **Evaluation:** Calculate the Silhouette Score for each model.
- **Visualization:** Plot the clustering results for each model.
- **Interpretation:** Analyze the characteristics of each cluster.

## How to Run

1. Clone the repository.
2. Ensure you have the required libraries installed: `pandas`, `scikit-learn`, `matplotlib`.
3. Run the Jupyter notebook or Python script to see the clustering analysis in action.

## Results

- The clustering analysis helps in identifying different segments of customers based on their income and spending patterns.
- The Silhouette Score provides a metric for evaluating the quality of the clusters.

## Future Work

- Experiment with different clustering algorithms.
- Include additional features like age in the analysis.
- Apply clustering to other datasets for comparison.

This project provides insights into customer segmentation, which can be useful for marketing strategies and business decisions.
