# Customer_Segmentation
## Customer Segmentation for Mall Customers Using K-Means Clustering Algorithm
K-Means Clustering is a popular unsupervised machine learning algorithm that partitions data into clusters based on their similarity. In the context of mall customer segmentation, this algorithm can be used to group customers based on their spending habits, demographics, and other relevant factors.
### Steps Involved for this Clustering:
1.	**Data Collection:** Gather relevant customer data, such as age, gender, annual income, spending score, and other relevant attributes.
2.	**Data Preprocessing:** Clean the data by handling missing values, outliers, and inconsistencies. Normalize or standardize the data to ensure all features have equal importance. Missingno library used for visualizing and handling missing data in datasets.    
3.	**Choosing the Number of Clusters (K):** Determine the optimal number of clusters using methods like the elbow method and silhouette analysis.
4.	**K-Means Clustering:** Apply the K-Means algorithm to the preprocessed data, specifying the chosen number of clusters. The algorithm iteratively assigns data points to the nearest cluster centroid and updates the centroids until convergence.   
5.	**Cluster Analysis:** Analyze the resulting clusters to identify patterns and characteristics. Visualize the clusters using scatter plots or other appropriate techniques.
6.	**Interpretation and Actionable Insights:** Interpret the characteristics of each cluster and develop targeted marketing strategies for each segment.
### Example Through Visualization:
![Image-1](https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-1.JPG)
<a href="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-1.JPG">Histogram plot</a>, showing customer segmentation into 3 Potential Segments:<br>
-      Age Distribution: Age Groups 28-35 are the most Frequent Users.
-      Annual_Income Distribution: Customers who have Annaul_Income Range $60 to $75,they are most frequent buyer.
-      Spending_Score Distribution: Maximum Spending_Score Groups are between the Range of 55 to 58.

<p align="center">
  <img src="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-2.JPG" alt="Pie Chart" width="600"/>
</p>
<a href="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-2.JPG">Pie Chart</a>, showing customer segmentation through Gender into 2 Segments:<br>
-     Gender Distribution: From this graph, we can see that most of the customers are Female and, their percentage is 56% and The lowest percentage of Males is 44%.easily illustrated 
       this, the female customers purchase more products.

  
•	High-Income Spenders: These customers have high annual incomes and high spending scores. They are likely to be interested in luxury brands and exclusive offers.
•	Middle-Income Spenders: These customers have moderate annual incomes and moderate spending scores. They are price-conscious but still willing to spend on quality products.
•	Low-Income Spenders: These customers have low annual incomes and low spending scores. They are likely to be attracted to discounts and promotions.
•	Low-Income Savers: These customers have low annual incomes but high savings rates. They are likely to be interested in value-for-money products and exclusive deals.
