# Customer Segmentation and Product Recommendation
[![](https://img.shields.io/badge/-K--Means-orange)](#) [![](https://img.shields.io/badge/-Classification-orange)](#) [![](https://img.shields.io/badge/-Student-blue)](#)

# Project objective
![image](HDI_ProjectObj.png)

# Dataset
HDI is distribution company supported by various effective health products for dynamic modern life such as health supplements, health supplements for kids, healthy food and drink, natural personal care and skin care.
### Data understanding
![image](HDI_EDA_1.png)
![image](HDI_EDA_2.png)

### Sanity check
![image](HDI_Sanity_1.png)
![image](HDI_Sanity_2.png)
![image](HDI_Sanity_3.png)

### Assumption
- Focus on total amount by ignoring paid amount because there are only 50K members were pain more than zero from total customer around 578K members.
- Using data from the most recent two months in 2023, recommend a product in each cluster due to computing power limitation.

# Create customer single view
list of feature
![image](HDI_CSV.png)

# Customer segmentation
![image](HDI_Segment.png)

### Feature Improtant
![image](HDI_FeatureImp.png)

# K-mean
Consider number of cluster by elbow and silhouette
![image](HDI_Elbow.png)

### Clustering result
![image](HDI_Scatter.png)

### Cluster interpretation
![image](HDI_Interpret.png)

# Product recommendation
Create user to user similarity metric in each cluster for recommended product.
![image](HDI_ProductRec.png)

### Performance eveluation
![image](HDI_Evaluate.png)
