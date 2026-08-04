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


<img width="311" height="262" alt="image" src="https://github.com/user-attachments/assets/d3cfe739-fa7a-481c-9c76-664ebca8abaf" />


<img width="411" height="380" alt="image" src="https://github.com/user-attachments/assets/d6aab227-5f1a-4fc5-8f06-e4d553e87c6f" />


<img width="848" height="458" alt="image" src="https://github.com/user-attachments/assets/e49a3c6e-7873-4784-9149-7a8eec0d503e" />


<img width="684" height="587" alt="image" src="https://github.com/user-attachments/assets/ec10ddda-6cf8-4800-a9e3-33342ddb136a" />


## Data Preprocessing

- Handled missing values
- Removed redundant columns
- Encoded categorical data
- Standardized numerical variables using Z-score standardization

## Power BI Dashboard

<img width="1045" height="587" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/4bc4f4a1-cb84-462d-a72c-039d92abb4c8" />


## Machine Learning Models

- K-Means
- Agglomerative Clustering
- Gaussian Mixture Model (GMM)

The models were compared for different values of k.

## Model Evaluation

To evaluate the models and to pick the best-performing one, the following metrics were used:
- Silhouette Score
- Calinski–Harabasz Score
- Davies–Bouldin
- Elbow Method (K-Means)
- AIC (Gaussian Mixture)
- BIC (Gaussian Mixture)
- Dendogram (Agglomerative Clustering)

     ### Dendogram (Agglomerative Clustering)
  
     ### AIC/BIC (Gaussian Mixture)
  
     ### Dendogram (Agglomerative Clustering)
     
     ### Silhouette Score
  
     ### Calinski–Harabasz Score
  
     ### Davies–Bouldin
  

## Clusters

## Business Recommendations

## Author
   Nombulelo Msibi
   

**LinkedIn:** www.linkedin.com/in/nombulelo-msibi-786b2466
  
**GitHub:** https://github.com/buleys
  
**Kaggle:** https://www.kaggle.com/buleys
  



