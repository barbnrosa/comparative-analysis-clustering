# Customer Personality Segmentation Project

## Overview
This project focuses on customer segmentation using unsupervised clustering techniques. The dataset utilized for analysis, obtained from Kaggle, centers around customer personality attributes and was chosen due to its relevance to the study's objective. The main goal is to compare the performance of three clustering algorithms: K-Means, DBSCAN, and Agglomerative Hierarchical Clustering.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
  - [Dataset Selection](#dataset-selection)
  - [Preprocessing](#preprocessing)
  - [Clustering Algorithms](#clustering-algorithms)
  - [Results](#results)
  - [Interpretation of Results](#interpretation-of-results)
- [Conclusion](#conclusion)

## Introduction

In today's data-driven world, understanding customer behavior is crucial for businesses to tailor their marketing strategies effectively. This project aims to segment customers based on their personality attributes using unsupervised clustering techniques. By grouping similar customers together, businesses can target their marketing efforts more precisely and enhance customer satisfaction.

## Methodology

### Dataset Selection

The dataset used in this project was obtained from Kaggle and includes various customer attributes such as age, education level, marital status, income, and spending behavior. These attributes provide valuable insights into customer preferences and behavior.

### Preprocessing

Before applying clustering algorithms, preprocessing steps were conducted to clean the data, normalize features, and reduce dimensionality using Principal Component Analysis (PCA). Dimensionality reduction enhances interpretability and reduces computational complexity.

### Clustering Algorithms

Three clustering algorithms were compared: K-Means, DBSCAN, and Agglomerative Hierarchical Clustering. The Elbow Method was used to determine the optimal number of clusters for K-Means and Agglomerative Hierarchical Clustering. The silhouette score was employed to evaluate the clustering models' performance, with K-Means demonstrating superior results.

### Results

The silhouette score indicated that K-Means outperformed DBSCAN and Agglomerative Hierarchical Clustering. Four distinct clusters were identified using K-Means, revealing different customer segments based on income and spending patterns.

### Interpretation of Results

Each cluster was analyzed to understand customer behavior and preferences. Profiles were created for each cluster, identifying likely customer types based on family structures, income levels, and spending habits.

## Conclusion

In conclusion, this project demonstrates the effectiveness of K-Means clustering in customer segmentation analysis. By identifying distinct customer segments, businesses can tailor marketing strategies to better meet the needs of different customer groups. This approach can lead to more targeted and personalized marketing campaigns, ultimately improving customer satisfaction and retention.
