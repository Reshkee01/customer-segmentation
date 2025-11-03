This project performs customer segmentation using the Mall Customers dataset to understand shopping behavior based on annual income and spending score. 
After loading the dataset and confirming that no missing or duplicate values exist, exploratory analysis is done through scatter plots to visualize income versus spending patterns. 
The K-Means clustering algorithm is applied by first identifying the optimal number of clusters using the Elbow Method, where the Sum of Squared Errors (SSE) is calculated for k values ranging from 1 to 8. 
The data is then scaled using MinMaxScaler for better clustering performance. With the optimal selection of 5 clusters, K-Means is trained on the normalized annual income and spending score features, and each customer is assigned a segment label. 
The resulting clusters reveal distinct customer groups, such as high-income high-spending, low-income low-spending, and other behavioral patterns. 
Visualizations show clearly separated clusters along with their centroids, helping businesses target specific customer groups for personalized marketing and strategy planning.
