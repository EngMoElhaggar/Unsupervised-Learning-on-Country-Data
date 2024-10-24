Clustering Countries Using Socio-Economic and Health Factors for HELP International
Project Overview
This project aims to categorize countries based on socio-economic and health factors to help HELP International, a humanitarian NGO, strategically allocate $10 million in aid. The NGO’s goal is to provide relief to countries in dire need by focusing on the most critical factors affecting overall development.

Objective
The primary objective is to use unsupervised learning techniques, specifically KMeans clustering, to group countries and suggest which countries need immediate aid. Key socio-economic and health factors were used for clustering, providing actionable insights for the NGO.

Approach
1. Data Preprocessing:
StandardScaler: To standardize the data and ensure all features contribute equally to the clustering algorithm, I applied StandardScaler. This helps in bringing all the features to the same scale, making the clustering process more effective.
2. Clustering:
KMeans: I applied KMeans clustering to group the countries based on the selected socio-economic and health factors. I experimented with different values for k to find the optimal number of clusters.
3. Tuning k (Elbow Method):
To determine the optimal number of clusters (k), I used the Elbow Method by plotting the inertia (within-cluster sum of squares) for a range of k values. This allowed me to select the k where adding more clusters provided diminishing returns.
Results
After applying the KMeans algorithm and tuning the optimal number of clusters, I identified distinct groups of countries based on their development factors. The countries in the cluster with the highest socio-economic need were recommended for receiving priority aid
