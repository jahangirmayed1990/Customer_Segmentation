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
<p align="center">
  <img src="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-3.JPG" alt="Histogram with Hue" width="600"/>
</p>
<a href="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-1.JPG">Histogram plot</a>, showing customer segmentation into 3 Potential Segments:<br>
-      Age Distribution: Age Groups 27-32 are the most Frequent Users.<br>
-      Annual_Income Distribution: Customers who have Annaul_Income Range $60 to $75,they are most frequent buyer.<br>
-      Spending_Score Distribution: Maximum Spending_Score Groups are between the Range of 55 to 58.<br>

<p align="center">
  <img src="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-2.JPG" alt="Pie Chart" width="600"/>
</p>
<a href="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-2.JPG">Pie Chart</a>, showing customer segmentation through Gender into 2 Segments:<br>
-            Gender Distribution: From this graph, we can see that most of the customers are Female and, their percentage is 56% and The lowest percentage of Males is 44%.<br>
             easily illustrated this, the female customers purchase more products.<br>

<p align="center">
  <img src="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-4.JPG" alt="Scatter Plot" width="600"/>
</p>
<a href="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-4.JPG">Scatter Plot</a>,
showing customer segmentation purpose Annual_income Vs Spending_Score plotting:<br>
-            Annual_income Distribution: From this plot, we can see that the maximum annual income above $125 is 3 persons who are Males.<br>

<p align="center">
  <img src="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-6.JPG" alt="Scatter Plot" width="600"/>
</p>
This K-Means Clustered<a href="https://github.com/jahangirmayed1990/Customer_Segmentation/blob/main/Image-6.JPG">Scatter Plot visualization</a>, showing customer segmentation by 5 nos.
Clustering purpose Annual_income Vs Spending_Score Scatter plotting:<br>
-            Annual_income Vs Spending_score Plotting: From this plot, we can see that the maximum annual income for customers clustering position is 1.
             In this clustering area, the target customers are those who have good Annual income and Spending Scores.<br>


### Customer Segmentation for Mall Customers Using K-Means Clustering: Insights
**Key Insights Gained from K-Means Clustering:**
1.	**Identification of Distinct Customer Segments:** <br>
- 	  High-Income Spenders: These customers have high annual incomes and high spending scores. They are likely to be interested in luxury brands, exclusive offers, and personalized services.
-     Middle-Income Spenders: These customers have moderate annual incomes and moderate spending scores. They are price-conscious but still willing to spend on quality products. They may be attracted to value-for-money deals and promotions.
-  	  Low-Income Spenders: These customers have low annual incomes and low spending scores. They are likely to be attracted to discounts, promotions, and budget-friendly options.
- 	  Low-Income Savers: These customers have low annual incomes but high savings rates. They are likely to be interested in value-for-money products and exclusive deals.
2.	**Targeted Marketing Strategies:** <br>
-    	Personalized Offers: By understanding customer segments, businesses can tailor marketing campaigns and offers to specific groups, increasing their effectiveness.
-    	Exclusive Promotions: Offering exclusive discounts and promotions to specific customer segments can incentivize spending and build loyalty.
-    	Product Recommendations: Based on spending patterns, businesses can recommend relevant products and services to customers, enhancing their shopping experience.
3.	**Optimized Inventory Management:** <br>
-    	Demand Forecasting: By analyzing spending patterns of different segments, businesses can optimize inventory levels to match demand, reducing the risk of stockouts or excess 
      inventory.
-    	Product Assortment: Tailoring product assortment to specific customer segments can attract more customers and increase sales.
4.	**Improved Customer Experience:** <br>
-    	Personalized Services: Offering personalized services, such as VIP treatment or exclusive shopping events, can enhance the overall shopping experience for high-value customers.
-    	Enhanced Store Layout: By understanding customer flow and preferences, businesses can optimize store layout to improve navigation and increase product availability for target 
      customer group.
