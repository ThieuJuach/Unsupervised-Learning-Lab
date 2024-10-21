Mall Customer Segmentation - Unsupervised Learning Lab

Project Overview

The goal of this project is to:

Perform exploratory data analysis (EDA) on the dataset.
Apply clustering algorithms such as K-Means and Agglomerative Clustering.
Use dimensionality reduction techniques like PCA and t-SNE to visualize high-dimensional data.
Evaluate the clustering results using the Silhouette Score.

Dataset

The dataset used is the Mall Customer Segmentation Dataset.
It contains 200 entries with the following features:
CustomerID: Unique identifier for each customer.
Gender: Gender of the customer.
Age: Age of the customer.
Annual Income (k$): Annual income of the customer in thousands.
Spending Score (1-100): Spending score assigned by the mall (higher is better).

Requirements

The following Python libraries are required to run the project:

pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

Project Structure

Data Exploration & Preprocessing

Loaded the dataset and displayed basic statistics.
Checked for missing values (none were found).
Scaled the features using StandardScaler for normalization.
Visualized relationships between features using pair plots and histograms.
K-Means Clustering

Implemented the elbow method to determine the optimal number of clusters (k=5).
Visualized the clusters using PCA for dimensionality reduction.
Hierarchical Clustering

Implemented Agglomerative Clustering with different linkage methods (ward, average, complete).
Visualized the results using a dendrogram.
Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce the dimensions of the data.
Created a 2D scatter plot for cluster visualization.
Applied t-SNE for further dimensionality reduction and visualization.
Evaluation (Silhouette Score)

Calculated and compared the Silhouette Scores for both K-Means and Agglomerative Clustering.

Results

K-Means Clustering:

The optimal number of clusters (k=5) was determined using the elbow method.
K-Means clustering produced well-separated clusters, which were visualized in 2D using PCA.
Silhouette Score for K-Means: 0.5547
Hierarchical Clustering:

Explored different linkage methods (ward, average, complete).
Dendrogram provided a visual representation of the hierarchical clustering process.
Silhouette Score for Hierarchical Clustering: 0.5531
PCA and t-SNE:

PCA explained a significant portion of the variance, and the first two principal components were used to visualize the clusters.
t-SNE provided an alternative way of visualizing clusters with clearer separations in some cases.

Visualizations

Elbow Curve for optimal k in K-Means.
Scatter Plot of clusters using PCA.
Dendrogram for hierarchical clustering.
t-SNE Scatter Plot for cluster visualization.
Explained Variance Plot for PCA.

Analysis & Discussion

The clustering algorithms provided similar results, with slightly better-defined clusters in K-Means based on the Silhouette Score.
PCA helped in reducing the dimensions of the data, which allowed for easier cluster visualization.
t-SNE provided clearer separation of clusters compared to PCA, highlighting the strengths of each dimensionality reduction technique.

Conclusion

This project successfully demonstrates the application of unsupervised learning techniques to cluster and analyze customer data. Through K-Means and Hierarchical Clustering, and with the help of dimensionality reduction techniques like PCA and t-SNE, meaningful insights into customer segmentation were gained. The results can help the mall better understand customer behavior and tailor their marketing strategies accordingly.

