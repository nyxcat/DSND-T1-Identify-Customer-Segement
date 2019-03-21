# Identify-Customer-Segement

## Introduction
In this project, real-life data provided to by Bertelsmann partners AZ Direct and Arvato Finance Solution was used. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. This project uses unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, the data is assessed and cleaned in order to convert the data into a usable form.

## Data
- Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.

## Word flow
1. Function clean_data() is provided to clean the customer and general population data. The cleaning involves missing value imputation, re-encoding features, one-hot encoding, and split dataset into 2 groups based on different number of missing values in row.
2. Principal component analysis (PCA) is applied to find the vectors of maximal variability.
3. Use the k-means method to cluster the demographic data into groups.
4. Apply the techniques and models that fit on the demographic data to the customers data: data cleaning, feature scaling, PCA, and k-means clustering. Compare the distribution of people by cluster for the customer data to that of the general population. 
5. Features of overrepresented and underrepresented clusters are analyzed
## 

## Requirement
python
numpy
pandas
matplotlib
seaborn
sklearn
