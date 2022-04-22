# Customer-segmentation
## Customer Relationship Management, Customer Segmentation, K-Means Clustering 


**Introduction**
Customer segmentation is mostly used to optimize your marketing strategies, maximize a customer's value to your business, and improve customer experience and satisfaction and This will increase the success of your marketing campaign


**Problem**
The marketing team can plan the strategy accordingly, and they must understand the customers, such as who are your target customers.


**Description of the dataset**
-Unique ID assigned to the customer
-Gender
-Annual income
-Age
-Score assigned by the mall based on customer behavior and spending nature

**Framing the problem**
clustering our customers into groups using  K-Means Clustering 


**Exploring the data – Heatmap – correlation**

'Annual Income (k$)' are correlated to our target variable ‘Spending Score (1-100)’. 
Variable ‘Age' are negatively correlated to ‘Spending Score (1-100)’
![image](https://user-images.githubusercontent.com/69022024/164135066-2dcda08d-8e1e-44b3-a6a0-e71a98f6f4ff.png)

**Visualization correlation**
![image](https://user-images.githubusercontent.com/69022024/164135154-bd5b1c15-13b9-4f46-81dc-735a8400913a.png)
![image](https://user-images.githubusercontent.com/69022024/164135177-df71a811-efff-4114-9213-a319ba3a4a1d.png)

**Visualization Age groups**
![image](https://user-images.githubusercontent.com/69022024/164135251-f0499f1f-b5da-4621-9950-ccb7599aa47e.png)

**Visualization count plot for gender**
![image](https://user-images.githubusercontent.com/69022024/164135360-f5fa1b0d-bcb9-476a-8274-333e44c46f20.png)
**Preparing the data**
> *Set the missing values to the mean*
**before**
![image](https://user-images.githubusercontent.com/69022024/164135431-1da5c55f-b770-4c1a-b0de-d08e508b7585.png)
**After**
![image](https://user-images.githubusercontent.com/69022024/164135462-d8e6d16b-029c-49d8-b914-19a939a75a54.png)

**Elbow method**
![image](https://user-images.githubusercontent.com/69022024/164135525-063a0d48-9f09-425f-b53a-6163ebc28055.png)

**Bulid model K-mean Cluster where k = 5**
![image](https://user-images.githubusercontent.com/69022024/164135622-a1aa51f8-84ce-4755-a4b2-0db9569624f9.png)


Now for each cluster, we can use different marketing strategies based on customer's behavior










