# Customer Segmentation

## Dataset:
Use the _**customer-data.csv**_ file to get the customer data used in this project. The dataset contains records of 10,000 customers who have ordered food from a food delivery service such as **’Vber Eats’**. Furthermore, it records features such as first and recent time of order, amount spent by customers and number of orders.

## Problem Statement:
**Vber Eats** is a food delivery service that is facing a problem in retaining their customers. It is now unto the analytics team to solve the problem of customer retention by leveraging sophisticated analytics tool and machine learning algorithms. The problem should be of great interest to any organization that works in customer service domain and the analysis presented in this project seeks to solve this problem. We can divide the problem statement in two parts:
- The customers who are not contributing to revenue (low performing customers) needs to be identified and segregated from the customers that generate a lot of revenue (high performing customers) for the organization.
- The identification of these customer segments needs to be based on certain key performance indicators, which also needs to be recognized from the dataset given.

## Methodology:
Python is used to perform the analysis in this project. The complete Python code can be found in the Jupyter Notebook named **’Customer Segmentation - RFM’**. The outline of the steps followed in the analysis is as follows:
- Data exploration and Validation (Performing data integrity checks, identifying missing values etc.)
- Data Preprocessing (Handling missing values, standardization, checking for correlation, testing hypothesis)
- Pareto Analysis (To determine what percentage of the customer contribute to what percent of the revenue)
- Determining the Key Performance Indicators.
- Determining the number of clusters through Elbow Analysis.
- K-Means clustering for Customer Segmentation.
- PCA for better visualization.
- Aggregate information for each cluster.

## Results and Conclusion:
- First, as suspected, one of the customer clusters really outperforms all other clusters and the customers in that cluster is truly our most valued customer. The company should try to protect them and keep been intact.
- On the other hand, cluster number 4 is the least performing cluster. The customers in this cluster have not ordered since a long time and they tend to not spend a lot too. The company can reach out to these customers for their feedback and design special marketing campaigns to earn back their business.
- There seems to be no difference between clusters in average distance from the restaurant and average delivery time.
- The selected key performance indicators, '# of Orders' (Frequency), 'Amount' (Monetary) and 'Recency' are actually statistically different in each cluster and remain key to segmenting customers into different clusters.

## Presentation:
Since this is a business proposition, communicating the results of this analysis remains one of the most important steps, not only in this project but in any other data analytics project. The document named **’Customer Segmentation- Presentation.pdf’** contains intuitive presentations with visualizations and provides comprehensible recommendations to the stakeholders.
