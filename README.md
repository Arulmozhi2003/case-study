# COSC2669 Case Study - Customer Analytics

This repository contains the analysis completed for COSC2669 Individual Task 1.

## Files

- `online_shoppers_svm.ipynb`  
  Support Vector Machine analysis using the Online Shoppers Purchasing Intention dataset.

- `online_retail_kmeans.ipynb`  
  K-means customer segmentation using the Online Retail dataset.

- `online_shoppers_intention.csv`  
  Dataset used for the SVM analysis.

- `Online Retail.xlsx`  
  Dataset used for the K-means analysis.

## Analysis

### 1. Purchase Intention Prediction
The Online Shoppers Purchasing Intention dataset is used to predict whether an online shopping session results in a purchase.

The analysis includes:
- data preparation
- encoding and standardisation
- Support Vector Machine classification
- model evaluation using accuracy, precision, recall, F1-score, ROC-AUC and Precision-Recall performance

### 2. Customer Segmentation
The Online Retail dataset is used to identify customer groups based on Recency, Frequency and Monetary behaviour.

The analysis includes:
- transaction cleaning
- creation of RFM features
- log transformation and standardisation
- K-means clustering
- silhouette-score comparison for selecting the number of clusters

## Running the Notebooks

1. Clone or download this repository.
2. Keep the dataset files in the same folder as the notebooks.
3. Open the notebooks in Jupyter Notebook or JupyterLab.
4. Run all cells from top to bottom.

## Dataset Sources

Online Shoppers Purchasing Intention Dataset  
UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

Online Retail Dataset  
UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/352/online+retail

## Author

Arulmozhi Ezhilarasi Arunachalam  
Student ID: S4138509
