# Zidio-Internship---Customer-Segmentation-Project-1
This project performs customer segmentation using K-Means clustering on e-commerce data, analysing customer behaviour through visualisations, and identifying key patterns for targeted marketing strategies.

This project aims to perform customer segmentation using K-Means clustering on an e-commerce dataset. The goal is to analyze customer behavior and identify key patterns for targeted marketing strategies. Below are the key steps and features of the project:

Data Loading and Preprocessing:

Import necessary libraries: numpy, pandas, matplotlib, seaborn, sklearn.
Load e-commerce customer data from an Excel file.
Clean the data by handling missing values and duplicates.
Exploratory Data Analysis (EDA):

Display basic information and statistical description of the dataset.
Visualize the distribution of categorical variables like gender using count plots.
Analyze the distribution of numerical variables using box plots.
Generate a heatmap to visualize correlations among features.
Feature Engineering:

Create a new feature Total Search which sums up search counts across different brands for each customer.
Visualize the top 10 customers based on total searches.
Data Normalization:

Normalize the features using MinMaxScaler to prepare for clustering.
K-Means Clustering:

Determine the optimal number of clusters using the elbow method and silhouette analysis.
Perform K-Means clustering with the optimal number of clusters.
Assign cluster labels to customers and save the clustered data to a CSV file.
Cluster Analysis:

Analyze the distribution of customers across clusters using count plots.
Visualize the total searches and orders for each cluster.
Perform a detailed analysis of clusters 0 and 2, focusing on gender distribution and total searches.
Overall Analysis:

Summarize the number of customers and their total searches and past orders in each cluster.
Provide visual insights using bar plots for total searches and orders across different clusters.
PDF Report:

Encode a PDF report in base64 and provide a download link for the report.
By completing this project, we gain insights into customer behavior, which can be leveraged for personalized marketing strategies, enhancing customer experience, and improving business outcomes
