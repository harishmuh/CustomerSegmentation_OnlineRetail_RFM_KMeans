![banner](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/customer%20segmentation.PNG?raw=true)

# Customer Segmentation of Online Retail by Using RFM Analysis and K-Means Clustering
## Context
### Customer-centric Online retail
Online retail or e-commerce refers to the process of buying and selling consumer goods or services over the Internet to earn profit. Unlike traditional retail, online retail businesses have access to vast amounts of data including 
purchase history, transactional data, demographic information, etc. Online retailers operate in a highly competitive environment, where understanding customer behavior is crucial for sustaining growth and profitability.
Customer-centric strategy can be the way to win the competition because Understanding customers’ needs, perceptions,  and expectations is crucial for stronger customer relationships & better business outcomes. 

### Customer segmentation
Customer Segmentation is crucial for online retail because it allows businesses to understand and cater to the diverse needs of their customers. By grouping customers based on their behavior, such as purchasing frequency, recent activity, and spending amount, retailers can create targeted marketing strategies that resonate with specific segments. This personalized approach not only improves customer satisfaction but also increases sales and customer retention, as it ensures that the right products and offers are presented to the right customers at the right time. Additionally, segmentation helps retailers operate their marketing costs efficiently as each customer segment typically incurs a different marketing cost.

## Problem statement
In this competitive online retail landscape, understanding customer diversity and tailoring marketing strategies to different customer segments is a critical challenge. Businesses must be able to identify and prioritize high-value customers while also re-engaging at-risk or lost customers. Without effective segmentation, marketing efforts can become inefficient, leading to wasted resources and missed opportunities to enhance customer loyalty and increase revenue. The ability to perform customer segmentation allows businesses to allocate marketing resources more effectively, optimize promotional strategies, and deliver personalized experiences that resonate with each customer group.

## Goals
Based on the identified problem, an online retail company based in the United Kingdom aims to implement a data-driven approach to customer segmentation. The goal is to develop a segmentation model that categorizes customers into distinct groups based on their purchasing behavior, frequency of transactions, and monetary value. The segmentation will be based on RFM (Recency, Frequency, Monetary) analysis and unsupervised machine learning techniques such as K-means clustering to ensure that each customer segment is accurately identified and targeted.

## Results

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/total%20product%20sold.PNG?raw=true)

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/total%20revenue%20overtime.PNG?raw=true)

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/RFM%20quantiles.PNG?raw=true)

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/RFM%20customer%20segmentation.PNG?raw=true)

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/elbow%20method%20silhoutte%20score.PNG?raw=true)

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/optimal%20cluster%20davies%20bouldin.PNG?raw=true)

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/tsne%20visualization%20snake%20plot.PNG?raw=true)


![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/cluster%20evaluation.PNG?raw=true)

## Insights

![image](https://github.com/harishmuh/CustomerSegmentation_OnlineRetail_RFM_KMeans/blob/main/insights%20kmeans.PNG?raw=true)

**Cluster 0 (At Risk Customers)**

* This cluster has 23% customers. It is characterized by customers who have not made a purchase for a long time (high recency), make purchases relatively infrequently (low frequency), and have spent less overall (low monetary). This cluster might represent inactive or lapsed customers who need re-engagement or could be at risk of being lost.

**Cluster 1 (Active Customers)**

* This cluster has 24% of customers. Customers in this cluster made a purchase more recently than Cluster 0 (moderate recency), have a moderate purchase frequency, and have spent a moderate amount. This group might represent active customers who are somewhat engaged with your offerings, making regular purchases but not at the highest frequency or monetary value.

**Cluster 2 (Best Customers)**

* This cluster has 52% of customers. Customers in Cluster 2 are the most recently engaged (low recency), have the highest purchase frequency, and have spent the most money. This cluster likely represents your best customers who are highly engaged and contribute significantly to your revenue. They may be the focus for retention and loyalty programs.

## Recommendations
**At-risk customers** (low recency, frequency, monetary): Re-engagement efforts that include running discounts or promotions to win them back)
* Reactivation Campaigns: Send personalized emails with special offers or discounts to encourage them to return. Consider highlighting products they previously showed interest in.
* Surveys: Reach out with a survey to understand why they stopped purchasing. Use this feedback to improve customer experience.
* Content Marketing: Share content that might reignite their interest in your products, such as blog posts, product reviews, or how-to guides.
* Retargeting Ads: Use retargeting ads to remind them of your products when they browse online.

**Active customers** (moderate frequency and monetary): Providing appreciation campaigns and rewards for loyalty
* Time-based Offers: Provide time-sensitive discounts or exclusive deals to create a sense of urgency.
* Loyalty Programs: Encourage repeat purchases by offering loyalty points for every purchase that can be redeemed for discounts or freebies.
* Personalized Recommendations: Use their purchase history to suggest new or related products.
* Customer Engagement: Send personalized follow-up emails after purchases, asking for reviews or offering tips on how to use the product.

**Best customers** (high frequency, high monetary): Focus on retention and more exclusive loyalty programs. Personalized special discounts and other premium perks to make them valued and appreciated
* VIP Treatment: Provide exclusive benefits such as free shipping, special discounts, or early access to sales and new products.
* Personalized Communication: Send personalized thank-you notes, anniversary emails, or birthday discounts to strengthen the relationship.
* Exclusive Offers: Offer them access to limited-edition products or invite them to special events.
* Referral Programs: Encourage them to refer friends and family by offering rewards for successful referrals.
