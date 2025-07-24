# Case-Study---Customer-Segmentation-using-Clustering-K-means

# Customer Segmentation with K-Means Clustering

## Project Overview

This project focuses on customer segmentation using the K-Means clustering algorithm. The goal is to group customers based on their purchasing behavior from a marketing wine campaign. We use clustering to identify similar patterns in purchase quantities and discounts, helping marketers better target each segment.

## Dataset

The dataset (`WineKMC.xlsx`) contains transaction-level information, including:

- Offer number  
- Campaign month  
- Varietal (type of wine)  
- Minimum quantity (kg)  
- Discount percentage  
- Country of origin  
- Whether the wine is past its peak  

## Methods Used

- Data Preprocessing: Removing non-numeric columns and scaling features  
- K-Means Clustering: Unsupervised learning to group customers  
- Elbow Method: To determine optimal number of clusters (K)  
- Silhouette Score: To validate clustering performance  
- PCA (Principal Component Analysis): To reduce dimensionality and visualize clusters  

## Key Steps

1. Load and explore the data  
2. Preprocess the data (remove non-numeric columns)  
3. Standardize features using `StandardScaler`  
4. Find the optimal number of clusters using:  
   - Elbow method  
   - Silhouette score  
5. Apply KMeans clustering  
6. Visualize clusters using PCA  

## Results

- The optimal number of clusters was determined to be 3  
- Customers were successfully grouped into 3 distinct segments based on purchasing behavior  
- PCA visualization shows clear separation among clusters  

## Files

- `Clustering Case Study - Customer Segmentation with K-Means - Tier 3.ipynb`: Final notebook with code and visualizations  
- `WineKMC.xlsx`: Raw data used in the analysis  

## Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (StandardScaler, KMeans, silhouette_score, PCA)  

## Conclusion

This project demonstrates how unsupervised learning techniques like K-Means can be effectively applied for customer segmentation. Understanding clusters allows businesses to personalize marketing strategies and improve campaign performance.


