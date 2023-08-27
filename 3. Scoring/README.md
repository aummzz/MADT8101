# Churn Scoring
[![](https://img.shields.io/badge/-Classification-orange)](#) [![](https://img.shields.io/badge/-Dataiku-green)](#) [![](https://img.shields.io/badge/-Student-blue)](#)

## Dataiku (https://www.dataiku.com/)
The world's leading platform for Everyday AI, systemizing the use of data for exceptional business results.
I use this tools to EDA, create model, parameter tuning, and deploy

## Dataset
![image](Churn_dataset.jpg)
![image](Churn_dataset_1.jpg)

## EDA
by Churn Flag

![image](Churn_EDA.jpg)

### Cleansing data
Remove rows with empty value in:
-  `Tenure ` 264 rows
-  `WarehouseToHome ` 251 rows
-  `HourSpendOnApp ` 255 rows
-  `OrderAmountHikeFromlastYear ` 265 rows
-  `CouponUsed ` 256 rows
-  `OrderCount ` 258 rows
-  `DaySinceLastOrder ` 307 rows

Total deleted 1,856 rows | Remain 3,774 rows

### Summary Statistics
![image](Churn_FeatureCorrelation.jpg)
![image](Churn_Correlation_SpliyByChurn.jpg)

### PCA variable
![image](Churn_PCA.jpg)

### Parallel Coordinates Plot
![image](Churn_ParallelCoordinatesPlot.jpg)

## Model Creation & Evaluation
Random dataset and split `Trainset ` and `Validateset `

- Using: `Random Forest `, `Logistic Regression `, `XGBoost `
- Metrics: `Precision `, `F1 score `
- Best performing Model: `Random Foreset `
![image](Churn_ModelPerformance.jpg)

## Feature Improtance
![image](Churn_FeatureImprotance.jpg)

### Confusion matric
![image](Churn_Metrix.png)

## Deploy Model
### Predict Churn Customer
![image](Churn_PredictSet.jpg)

### Classification
- KMean = 4
![image](Churn_KMeans.jpg)

### Segmentation
![image](Churn_Segmentation.png)

## Action
### Focus group
![image](Churn_Table.png)

### Marketing Plan
![image](Churn_Action.png)
