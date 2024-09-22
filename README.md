# E-commerce Customers Segmentation
  This project demonstrates how unsupervised machine learning can be used to segment E-commerce customers based on their transactional behaviors and demographics. By analyzing these segments, we can develop personalized coupon strategies to improve customer satisfaction and retention
  
First, I loaded and merged the data from the five tables into a single dataset.

Next, I created meaningful features that represent the customer’s coupon usage. For each customer, I compute:

The number of transactions they’ve completed.
The burn rate, which is the ratio of coupons claimed vs. those redeemed (burnt).

Then I used the K-Means clustering algorithm to segment customers into distinct groups based on their demographic and transactional behaviors. Before applying K-Means, I normalize the features to ensure the algorithm performs well and evaluate the clustering model using metrics like the Silhouette Score to measure how well the customers are grouped into distinct segments. A higher score indicates better clustering

at the end for analyzing I used visualization
