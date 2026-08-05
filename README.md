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
 
  <img width="1077" height="356" alt="image" src="https://github.com/user-attachments/assets/489534ba-5f5f-44b0-8c86-6d14fd93e6da" />

  <img width="1064" height="361" alt="image" src="https://github.com/user-attachments/assets/b97e6f68-0dea-4e36-bbd0-c51c19949afd" />

  <img width="1061" height="340" alt="image" src="https://github.com/user-attachments/assets/6fe214e1-9e2c-4011-a6c3-944de0a3cb64" />




## Clusters

#### PCA
<img width="770" height="531" alt="image" src="https://github.com/user-attachments/assets/e5ba2976-9d77-4ddd-8f4a-a74b0b4e81ff" />

**Cluster 0** - 

**Cluster 1** - 

**Cluster 2** - 

<img width="758" height="509" alt="image" src="https://github.com/user-attachments/assets/6af8290b-93a7-42db-a01a-2b0e6bb827e8" />

## Business Recommendations

## Author
   Nombulelo Msibi
   

**LinkedIn:** www.linkedin.com/in/nombulelo-msibi-786b2466
  
**GitHub:** https://github.com/buleys
  
**Kaggle:** https://www.kaggle.com/buleys
  



