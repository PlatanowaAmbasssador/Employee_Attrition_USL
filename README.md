# Employee Attrition Clustering Analysis

Employee attrition is a critical challenge for organizations, as high turnover can lead to increased costs and decreased productivity. This project explores clustering techniques to analyze employee attrition patterns using the IBM HR Analytics Attrition dataset from Kaggle. The dataset contains various employee attributes, including demographic, job-related, and performance-related factors.

## Overview

In this study, three clustering methods—K-Means, Partitioning Around Medoids (PAM), and Hierarchical Clustering—are applied to identify meaningful groups within the dataset. Initially, clustering is performed without dimensionality reduction. Then, dimensionality reduction techniques, namely Principal Component Analysis (PCA) and Multi-Dimensional Scaling (MDS), are employed to reduce the dataset’s complexity before applying the clustering algorithms. Hierarchical Clustering is also performed on the reduced datasets to assess its effectiveness in identifying employee groups.

To determine the optimal number of clusters, the Elbow Method based on Within-Cluster Sum of Squares (WCSS) and Silhouette Analysis are utilized. The results from different clustering approaches are compared to evaluate the impact of dimensionality reduction on clustering performance.

## Files Included

- `USL_1_2.Rmd` - R Markdown file containing the analysis
- `USL_1.Rproj` - R project file
- `USL_1_2.html` - HTML report of the analysis
- `data/` - Folder containing the dataset
- `images/` - Folder with visualization outputs
- `style.css` - Custom stylesheet for the report

## View the Full Report

[![View on RPubs](https://img.shields.io/badge/View%20Report-RPubs-blue?style=for-the-badge&logo=r&logoColor=white)](https://rpubs.com/Bhaiyuu_KK/employee_attrition)
