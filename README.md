# Wholesale Customer Segmentation and Analysis Project

---

Project Overview:

This project uses a specialized computer program (Clustering/Unsupervised Learning) to study how wholesale customers buy and to divide them into groups. Our main goal is to find distinct customer groups based on their annual spending data across six types of products. This, in turn, helps the distributor organize marketing and other operations correctly.

--- 

# Methodology:

1.  **Exploratory Data Analysis (EDA):** Performed to identify data distributions
2.  **Data Preprocessing:** Standard Scaling
3.  **Visualization:** scatterplot, plot-radar, subplot 
4.  **Clustering:**  **K-Means algorithm**,**Hierarchical Clustering** ,**Dendrogram**, **Elbow Method**,**Silhouette Score**.
Also used

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
---

# Results:

KMeans_Cluster
0     [Grocery, Milk]
1    [Fresh, Grocery]
2     [Frozen, Fresh]

Cluster 0 (Grocery, Milk): These customers purchase staple products in large volumes. They should be offered price discounts (volume discounts) and reliable supply chain consistency.

Cluster 1 (Fresh, Grocery): This group focuses on high-quality and fresh products. Offering them priority (or pre-delivery) of fresh goods or a limited (premium) range of new products may be effective.

Cluster 2 (Frozen, Fresh): This segment seeks quality and specialized products. Target them with value-added services (e.g., specialized storage solutions for frozen goods) or show them an expanded catalog of new product selections.

Silhouette Score (K-Means): 0.5482872649700601 ,This score is excellent. Your segments are very clear and well-separated from one another. In practice, a score above 0.5 is considered highly successful.

KMeans_Cluster is better than Hierarchical_Cluster



