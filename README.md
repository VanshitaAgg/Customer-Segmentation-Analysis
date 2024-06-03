# Customer-Segmentation-Analysis
Customer segmentation analysis is a key strategy in marketing and business intelligence, used to divide a customer base into distinct groups or segments. These groups share similar characteristics, behaviors, or needs, allowing businesses to tailor their marketing efforts and product offerings more effectively.

This project aims to perform customer segmentation on a Mall customer dataset using the K-Means clustering algorithm. The dataset contains information about customers such as their age, gender, annual income, and spending score. The goal of this project is to cluster the customers based on their purchasing behavior and demographic characteristics.

# Dataset
The dataset used in this project is mall-customers-data.csv. It contains 200 rows and 5 columns:

* CustomerID: unique ID assigned to the customer.
* Gender: gender of the customer (male or female).
* Age: age of the customer.
* Annual Income (k$): annual income of the customer in thousands of dollars.
* Spending Score (1-100): score assigned by the mall based on customer behavior and spending nature.

# Methodology
The analysis involves the following steps:
1. Data Preprocessing:
    * Load the dataset
    * Handle missing values
    * Encode categorical variables
    * Standardize the features

2. Exploratory Data Analysis (EDA):
   * Visualize the distribution of data
   *  Analyze correlations between variables

3. Clustering:
     * Use the K-Means clustering algorithm
     * Determine the optimal number of clusters using the Elbow method
     * Apply PCA for dimensionality reduction

4. Visualization:
     * Visualize the clusters in a 2D and 3D space using PCA components

# Results
After performing the analysis, we identified distinct customer segments based on their annual income and spending scores. The results are visualized using various plots to provide insights into customer behavior and characteristics.
