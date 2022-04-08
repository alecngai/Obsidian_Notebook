# Supervised 
Training set includes solution aka "labels"

learning algorithims 
- K-Nearest Neighbors
- Linear Regression 
- Logisitcal Regression
- Support Vector Machines (VSM)
- Decision Trees and Random Forest
- Neural networks

A set of features i.e. (mileage, age brand, etc.) are called "Predictors"

Attribute is a data type e.g ("mileage")
Feature is Attribute + Value 
Many people use feature / attribute interchangable. 


# Unsupervised

Training set has no labels

Learning Algorithms
- Clustering
	- K-Means
	- DBSCAN
	- Hierarchical Cluster Analysis (HCA)
- Anomaly detectionm and novelty detection
	- One-class SVM
	- Isolation Forest
- Visualization and dimensionality reduction
	- Principal Component Analysis (PCA)
	- Kernel PCA
	- Locally Linear Embedding (LLE)
	- t-Distributed Stochastic Neiighbor Embedding (t-SNE)
- Associated rule learning
	- Apriori
	- Eclat

A related task is "dimensionality reduction" simplify the data without losing infomation, merge several correlated features into one, this is called feature extraction. e.g. car's mileage, age, combined into new feature car's wear and tear. 

Dimensionality reduction algorithm before you feed machin learning algorithm to increase preformance, and maintain accuracy. 


# Semi - Supervised 
Training set with only some data labeled 