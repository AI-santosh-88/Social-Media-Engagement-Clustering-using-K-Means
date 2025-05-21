🔹 Business Use Case:
Identifying Content Strategies Through Engagement Clustering
# Problem:
 Social media pages publish various types of content (videos, photos, links, status updates), and user interactions vary across these content types. Understanding which content types lead to high engagement can help optimize future content strategies.
# Objective:
 Use unsupervised machine learning (K-Means Clustering) to group social media posts based on user engagement metrics to identify patterns in audience interaction and optimize content strategies.
----------------------------------------------------------------------------------------

# TItle :
Social Media Engagement Clustering using K-Means

# Description:
This project analyzes Facebook post-level data to cluster posts based on their engagement metrics such as reactions, comments, shares, and emotions (likes, loves, wows, etc.). The primary goal is to understand how different types of posts (video, photo, link, status) perform and what patterns emerge in user interaction.
The workflow includes:
* Data cleaning and preprocessing
* Feature encoding and normalization
* Clustering using K-Means
* Evaluation using confusion matrix and accuracy estimation
* Elbow method to identify optimal number of clusters
  
# Responsibilities:
1.DataCleaning & Preparation
* Handled null values
* Dropped irrelevant columns (Column1 to Column4, status_id, status_published)
2.Feature Engineering
* Encoded categorical variable (status_type) using LabelEncoder
* Applied MinMaxScaler for normalization
3.Modeling & Evaluation
* Trained K-Means model with different cluster numbers (2–4)
* Evaluated using accuracy and confusion matrix after aligning cluster labels
* Used elbow method to determine optimal clusters
4.Insights & Reporting
* Identified optimal cluster configuration
* Gained insight into how different content types engage audiences differently
  
# Packages & Libraries Used:
1.pandas – Data manipulation
2.numpy – Numerical computation
3.matplotlib, seaborn – Data visualization
4.sklearn.preprocessing – LabelEncoder, MinMaxScaler
5.sklearn.cluster – KMeans
6.sklearn.metrics – confusion_matrix
7.scipy.optimize – linear_sum_assignment for label matching

# Summary:
 project used unsupervised learning (K-Means Clustering) to segment social media posts by their engagement levels. By encoding the post types and scaling numeric metrics, the model clustered posts and evaluated their accuracy against actual post types. The elbow method suggested the ideal number of clusters. The results provided insights into how users react to different types of content, offering strategic guidance for future social media campaigns.




























