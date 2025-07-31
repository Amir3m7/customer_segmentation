Customer Segmentation Using Mall Customer Dataset
=================================================

A machine learning project to segment mall customers based on **Age**, **Annual Income**, and **Spending Score** using clustering algorithms.  
This helps marketing teams create targeted campaigns and improve store profitability.

* * *

Table of Contents
-----------------

- [About the Project](#about-the-project)  
- [Dataset](#dataset)  
- [Results](#results)  
- [Business Insights](#business-insights)  


* * *

About the Project
-----------------

- Uses **unsupervised learning** to identify customer groups  
- Implements **K-Means**, **DBSCAN**, **Hierarchical Clustering**, and **Mean Shift**  
- Compares algorithms with **Silhouette Score**  
- Provides **business recommendations** for each segment  

* * *

Dataset
-------

- **Source:** [Mall Customer Segmentation Data – Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- **Records:** 200 customers  
- **Features:**
  - `CustomerID` – Unique ID  
  - `Age` – Integer  
  - `Annual Income (k$)` – Numeric  
  - `Spending Score (1–100)` – Numeric  
  - `Gender` – Categorical (excluded from clustering)  

* * *

Results
-------

* **K-Means**: Best segmentation with 5 clusters  
* **Hierarchical (Complete Linkage)**: Performs better with 3 features  
* **DBSCAN & Mean Shift**: Less optimal but reveal interesting patterns  

### Identified Clusters:

1. Low income, high spending  
2. Medium income, medium spending  
3. High income, low spending  
4. High income, high spending  
5. Low income, low spending  

* * *

Business Insights
-----------------

* 🟢 **Young high-spenders** → Exclusive offers, digital marketing  
* 🟢 **High-income low-spenders** → Premium branding, luxury experiences  
* 🟢 **Budget-conscious customers** → Discounts, loyalty programs  

* * *
