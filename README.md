# Customer Segmentation Using Unsupervised Machine Learning

## Project Overview
Some businesses often treat all customers the same, resulting in inefficient campaigns. This project applies unsupervised machine learning techniques to segment customers based on purchasing behavior and demographics. The insights can help businesses develop targeted marketing strategies to improve customer retention. 

## Objectives

* Explore and understand customer purchasing behavior.
* Clean and process customer data.
* Build customer segments using clustering algorithms.
* Compare different clustering techniques.
* Interpret the characteristics of each customer segment
* Provide business recommendations

## Dataset

This project uses the Customer Shopping Behavior Dataset, which was obtained from a public GitHub repository.
  
  Source: https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI/blob/main/Customer%20Shopping%20Behavior%20Analysis.pdf
  
The dataset contains customer demographics and purchasing information, including:
- Age
- Gender
- Subscription status
- Purchase frequency
- Product category
- Season
- Review rating
- Discount usage

     **Total observations:** 3900
  
     **Total features:** 18

 
**Note:** The dataset was created by the original repository author. This project uses the dataset solely for educational purposes. All credit goes to Amlan Mohanty.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Project Overflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Encoding
5. Feature Scaling
6. Clustering
7. Model Evaluation
8. Cluster Interpretation
9. Business Recommendations

## Exploratory Data Analysis
The data was summarised to show the main characteristics and to extract information that a model may overlook. 
Below are some of the visuals from the EDA section:

<img width="543" height="457" alt="image" src="https://github.com/user-attachments/assets/c215b2c2-5bb2-4c96-9a4a-2381c12561e2" />


<img width="569" height="463" alt="image" src="https://github.com/user-attachments/assets/bdee8a6d-9b00-45e8-b305-3b6875141030" />


<img width="702" height="539" alt="image" src="https://github.com/user-attachments/assets/5329770c-0952-4d49-a2ad-f6c591ae2baa" />


<img width="848" height="458" alt="image" src="https://github.com/user-attachments/assets/e49a3c6e-7873-4784-9149-7a8eec0d503e" />


<img width="684" height="587" alt="image" src="https://github.com/user-attachments/assets/ec10ddda-6cf8-4800-a9e3-33342ddb136a" />


## Data Preprocessing

- Handled missing values
- Removed redundant columns
- Encoded categorical data
- Standardized numerical variables using Z-score standardization

## Power BI Dashboard

<img width="1045" height="587" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/4bc4f4a1-cb84-462d-a72c-039d92abb4c8" />

## Determine Optimal Number of Clusters
Elbow Method (K-Means), Dendogram (Agglomerative Clustering), AIC (Gaussian Mixture), and BIC (Gaussian Mixture) were used to determine the optimal number of clusters. 

<img width="839" height="538" alt="image" src="https://github.com/user-attachments/assets/d10d551d-a7f3-467f-81a7-4e82c83af929" />

<img width="709" height="445" alt="image" src="https://github.com/user-attachments/assets/87a4f0f2-ae3e-47ed-800d-5c7bfe0f2d12" />

<img width="558" height="388" alt="image" src="https://github.com/user-attachments/assets/77bb9bae-a054-4f7d-b6ba-46bab39796a1" />


## Machine Learning Models
Systematic hyperparameter comparisons were applied for the following models: 

- K-Means
- Agglomerative Clustering
- Gaussian Mixture Model (GMM)

## Model Evaluation

To evaluate the models and to pick the best-performing one, the following metrics were used:
- Silhouette Score
- Calinski–Harabasz Score
- Davies–Bouldin

 <img width="1067" height="334" alt="image" src="https://github.com/user-attachments/assets/673a198d-0f78-4136-8686-8a2b52bc286b" />

 <img width="1060" height="331" alt="image" src="https://github.com/user-attachments/assets/9a7a6a1b-f7d9-446f-b79b-3becc17d3b1d" />

 <img width="1059" height="336" alt="image" src="https://github.com/user-attachments/assets/0df60e40-cb44-4e0d-81fc-389da1463015" />

Athough both the Agglomerative Clustering and Gaussian Mixture Models performed well across the indices, K-Means consistently produced the lowest Davies-Bouldin Index, and it  demonstrated the most balanced overall performance, indicating more compact and well-separated clusters. The performance differences between the algorithms were relatively small, suggesting that all three produced meaningful cluster structures. 

Considering its competitive performance across the evaluation metrics, computational efficiency, ease of interpretation and profiling, and widespread use in customer segmentation, K-Means was selected as the final clustering algorithm

**Parameters that will be used in K-Means:



## Clusters

#### PCA
<img width="770" height="531" alt="image" src="https://github.com/user-attachments/assets/e5ba2976-9d77-4ddd-8f4a-a74b0b4e81ff" />

#### Profiling Clusters
<img width="796" height="129" alt="image" src="https://github.com/user-attachments/assets/45345282-25a5-4a0c-b055-ce51c68fa9d6" />

**Cluster 0 - High-Value Loyal Customers**

This cluster represents the business's most valuable customers. They made the highest number of previous purchases, indicating strong customer loyalty and a high likelihood of repeat business. They also spend relatively large amounts per purchase while providing the highest review ratings, suggesting a high level of satisfaction with the products they purchase. Additionally, they purchase more than the other clusters. This segment is essential for maintaining revenue and

**Cluster 1 - Budget-Conscious Regular Customers**

Cluster 1 consists of customers who spend the least amount per transaction despite having a relatively high number of previous purchases. Their review ratings indicate a generally positive experience, providing an opportunity to strengthen the relationship with this segment. They appear to be price-sensitive and may respond well to discounts, coupons, bundled offers, or promotional campaigns aimed at increasing purchase value and improving customer satisfaction. They are also a good target for upselling.

**Cluster 2 - Occasional Customers**

This cluster includes customers who spend relatively high amounts when they make a purchase but have made relatively few purchases overall. They have the lowest overall revenue because of the small size and infrequent purchases. Their review ratings indicate a generally positive experience, providing an opportunity to strengthen the relationship with this segment. These customers have the potential to become loyal, high-value customers if encouraged through personalized recommendations, targeted promotions, and retention campaigns.

<img width="783" height="389" alt="image" src="https://github.com/user-attachments/assets/07337aca-7d16-4aa0-9fdd-6097b465f032" />

The model successfully separated the absolute least frequent buyers into their own distinct segment. They only buy once a year. Purchase frequency does not differentiate these two segments. Both groups are active, highly regular shoppers who buy at various intervals throughout the year. Because the Budget-Conscious and High-Value segments look identical here, their true difference lies entirely in how much money they spend, not how often they visit.

<img width="776" height="384" alt="image" src="https://github.com/user-attachments/assets/b07276bb-3b4f-4314-b5c5-f57429c55263" />

Age is more or less evenly distributed across the entire customer base. The segments are purely behavioral, meaning that they are driven by how the customers buy and how much they spend, rather than demographic.

#### Radar Chart

<img width="758" height="509" alt="image" src="https://github.com/user-attachments/assets/6af8290b-93a7-42db-a01a-2b0e6bb827e8" />

The radar chart highlights clear behavioral differences among the three customer segments. Cluster 0 exhibits the strongest customer value, characterized by high purchase amounts, numerous previous purchases, and positive review ratings. Cluster 1 consists of regular but lower-spending customers. Cluster 2 is distinguished by its significantly longer purchase intervals and lower purchase activity, suggesting these customers may require targeted retention strategies to improve engagement.

## Business Recommendations


<img width="620" height="136" alt="image" src="https://github.com/user-attachments/assets/3552d3f7-0064-46f9-9a37-19271588781e" />


## Author
   Nombulelo Msibi
   

**LinkedIn:** www.linkedin.com/in/nombulelo-msibi-786b2466
  
**GitHub:** https://github.com/buleys
  
**Kaggle:** https://www.kaggle.com/buleys
  



