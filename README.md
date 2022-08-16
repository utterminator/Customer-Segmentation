# Customer-Segmentation
In this project, i trained unsupervised machine learning algorithms to perform customer market segmentation.
Market Segmentation enables sellers to create targeted marketing messages for a specific group of customers which increases the chances of the person buying a product. This helps the companies in establishing better customer relationships and their overall performance as an organization.
##dataset
 Credit card data is collected from kaggle dataset.
A customer credit card information dataset can be applied to targeted marketing, customer segmentation, and other similar use cases in the marketing sector.

**##Attributes information
BALANCE	, BALANCE_FREQUENCY,	PURCHASES, 	ONEOFF_PURCHASES, 	INSTALLMENTS_PURCHASES	, CASH_ADVANCE	, PURCHASES_FREQUENCY,	ONEOFF_PURCHASES_FREQUENCY, 	PURCHASES_INSTALLMENTS_FREQUENCY	, CASH_ADVANCE_FREQUENCY, 	CASH_ADVANCE_TRX	, PURCHASES_TRX	,CREDIT_LIMIT, 	PAYMENTS, 	MINIMUM_PAYMENTS	, PRC_FULL_PAYMENT	, TENURE


**##libraries**
Used libraries like Numpy, seaborn, pandas, matplotlib,scikit learn etc



**##Methods**
Found the correlation matrix between different features.
k- means clustering is used for grouping the customers into different clusters.
Principal component analysis(PCA) is used to reduce the number of variables 



**##Findings**
segmented customers into 7 clusters using the elbow mwthod and then applied k-means clustering.
For better visualisation, I applied PCA and reduced to two principal componentsand used seaborn library to visualise the different clusters.
