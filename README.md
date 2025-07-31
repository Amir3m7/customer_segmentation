🛍️ Customer Segmentation Using Mall Customer Dataset
📌 Project Overview
This project focuses on segmenting mall customers into distinct groups based on their age, annual income, and spending score using unsupervised machine learning algorithms. The goal is to help marketing teams design targeted campaigns and improve store profitability.
 
🚀 Features
•	✅ Exploratory Data Analysis (EDA) with visualizations
•	✅ Data preprocessing and normalization
•	✅ Implementation of multiple clustering algorithms:
o	K-Means
o	DBSCAN
o	Hierarchical Clustering (Complete Linkage, Average Linkage)
o	Mean Shift
•	✅ Comparison of clustering performance using metrics such as Silhouette Score
•	✅ Business insights and marketing strategies for each customer cluster
📂 Dataset Overview
•	Source: Kaggle – Mall Customer Segmentation Data
•	Records: 200 customers
•	Features:
o	CustomerID – unique identifier
o	Gender – categorical (excluded from clustering)
o	Age – numerical
o	Annual Income (k$) – numerical
o	Spending Score (1–100) – numerical
Gender was excluded from clustering to avoid misleading results in distance-based algorithms like K-Means.
🧠 Key Findings
•	K-Means (k=5) segmented customers into five groups based on income and spending patterns.
•	Hierarchical Clustering (Complete Linkage) gave the best results when including age as a third feature.
•	Younger customers tend to have higher spending scores.
•	Marketing strategies were designed for each identified cluster to maximize profitability.
 
📊 Business Value
By analyzing customer clusters, businesses can:
•	Deliver personalized offers to high-value customers
•	Improve conversion rates
•	Optimize marketing budgets
•	Enhance operational efficiency

![Uploading image.png…]()
