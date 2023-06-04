# Customer-Segmentation<br>
This project aims to perform customer segmentation using a dataset obtained from Kaggle. The goal is to identify distinct customer segments based on their shared characteristics and behaviors. This README file provides an overview of the project and guides you through the steps involved in customer segmentation.<br>

## Dataset<br>
### Invoice information:<br>

InvoiceNo - Unique ID for the invoice.<br>
InvoiceDate - Date and time of the invoice.<br>
### Item information:<br>

StockCode - Unique ID for the item.<br>
Description - Text description of the item.<br>
Quantity - Number of units per pack for the item.<br>
UnitPrice - Price per unit in GBP.<br>
### Customer information:<br>

CustomerID - Unique ID for the customer.<br>
Country - Country of the customer.<br>

## Data Preprocessing

Handling missing values<br>
Handling categorical variables<br>
Feature scaling<br>
Principal Component Analysis (PCA)<br>

Understanding PCA and its purpose<br>
Applying PCA to the dataset<br>
Interpreting the principal components and their variance explained<br>
Clustering Algorithms<br>

Overview of clustering algorithms (e.g., K-means)<br>
Choosing an appropriate clustering algorithm for customer segmentation<br>
Applying the selected clustering algorithm to the PCA-transformed data<br>
Evaluating and Visualizing Customer Segments<br>

Assessing cluster quality and determining the optimal number of clusters<br>
Visualizing the customer segments using various plots (e.g., scatter plot, box plot)<br>