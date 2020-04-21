# loan-default-prediction

## Overview 

This repository contains different approaches to predict loan defaults based on the past user history. There are different techniques and machine learning models implemented to analyze the results for a comparison as shown in the flow chart below. 
![](https://github.com/guptavasu1213/credit-card-default-prediction/blob/master/FlowChart.png)

A huge challenge with this dataset was the imbalancement of classes. For most machine learning algortihms to perform well, the class distribution should be around equal. However, the number of defaulters is only 8% of the entire dataset. There are a few techniques implemented like Oversampling and Undersampling to make the class ratio equal.  

This is a type of supervised classification problem which uses 0 and 1 as labels to indicate the loan default or non-default respectively. The data includes over 300,000 entries of loan applications with its corresponding success or failures. The dataset contains 122 columns which include the features like income, age, number of children etc. leading to the prediction.

## Prerequisites
- The dataset can be downloaded from: https://www.kaggle.com/mishra5001/credit-card
- Anaconda installed from: https://docs.anaconda.com/anaconda/install/
- Downloading the imbalanced-learn library by running:
```
conda install -c conda-forge imbalanced-learn 
```

## Status
The project is finished.

## Authors
* Vasu Gupta 
* Xavier Kidston
