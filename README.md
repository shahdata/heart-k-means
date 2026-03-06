# heart-k-means
Heart Disease Analysis Using K-Means Clustering in SAS

**Overview**

This project performs K-Means clustering on a cardiovascular disease dataset (heart.csv) to identify natural groupings among patients based on heart disease indicators. The analysis explores patterns in the data and evaluates the optimal number of clusters using SAS procedures.

The dataset contains 13 numerical/categorical features and 1 binary target variable indicating the presence or absence of heart disease. Clustering results are visualized and compared with the original labels to gain insights into patient risk profiles.

**Objectives**

Import and explore the heart.csv dataset using SAS.

Perform basic statistical analysis to summarize the dataset.

Standardize numerical variables for clustering.

Apply K-Means clustering with varying cluster numbers (k=2,3,4,5) using PROC FASTCLUS.

Evaluate cluster solutions using RMS Standard Deviation and choose the optimal number of clusters.

Visualize clusters against key features (cholesterol vs age) to interpret patterns.

**Dataset**

File: heart.csv

Features: 13 attributes (numerical/categorical) + 1 binary target

Target: heart_disease (0 = absence, 1 = presence)
