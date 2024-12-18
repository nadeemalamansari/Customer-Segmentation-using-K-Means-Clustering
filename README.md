# Customer-Segmentation-using-K-Means-Clustering
• Implemented K-Means clustering for customer segmentation based on purchasing behavior and demographics.  • Visualized clusters using PCA for dimensionality reduction.
# Customer Segmentation using K-Means Clustering

## Overview:
The "Customer Segmentation using K-Means Clustering" project utilizes the K-means clustering algorithm to categorize supermarket customers based on their spending behavior. The primary objective is to identify distinct customer segments and devise targeted marketing strategies to enhance customer engagement and satisfaction.

Dataset on Kaggle: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Process:
1. **Loading and Exploring Data:**
   - The dataset is loaded into a Pandas DataFrame.
   - Basic exploratory data analysis is performed, including examining the first five rows, checking the data shape, and reviewing data information for insights.

2. **Data Preprocessing:**
   - Missing values are checked and found to be absent.
   - The relevant columns for clustering (Annual Income and Spending Score) are selected.

3. **Determining Optimal Clusters:**
   - The "Elbow Method" is employed to determine the optimal number of clusters.
   - The Within-Cluster-Sum-of-Squares (WCSS) is plotted against the number of clusters.

4. **Training K-Means Model:**
   - The K-means clustering model is trained with the optimal number of clusters determined from the elbow method.
   - Labels are assigned to each data point based on their respective clusters.

5. **Visualization:**
   - The clustered data points are visualized in a scatter plot.
   - Each cluster is represented by a distinct color, making it easy to discern different customer groups.
   - The plot illustrates the relationship between Annual Income and Spending Score for each customer segment.
     
     ![image]

