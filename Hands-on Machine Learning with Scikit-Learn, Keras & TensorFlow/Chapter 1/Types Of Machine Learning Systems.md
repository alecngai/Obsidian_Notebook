# Supervised 
Training set includes solution aka "labels"

learning algorithms 
- K-Nearest Neighbors
- [[Linear Regression]] 
- Logistical Regression
- Support Vector Machines (VSM)
- Decision Trees and Random Forest
- Neural networks

A set of features i.e. (mileage, age brand, etc.) are called "Predictors"

An attribute is a data type, e.g ("mileage")
feature is Attribute + Value 
Many people use feature / attribute interchangeable. 


# Unsupervised

Training set has no labels

Learning Algorithms
- Clustering
	- K-Means
	- DBSCAN
	- Hierarchical Cluster Analysis (HCA)
- Anomaly detection and novelty detection
	- One-class SVM
	- Isolation Forest
- Visualization and dimensionality reduction
	- Principal Component Analysis (PCA)
	- Kernel PCA
	- Locally Linear Embedding (LLE)
	- t-Distributed Stochastic Neighbor Embedding (t-SNE)
- Associated rule learning
	- Apriori
	- Eclat

A related task is "dimensionality reduction" to simplify the data without losing information, merge several correlated features into one, this is called feature extraction. e.g. car's mileage, age, combined into new feature car's wear and tear. 

Dimensionality reduction algorithm before you feed machine learning algorithm to increase performance, and maintain accuracy. 


# Semi-Supervised 
Training set with only some data labeled 

For example, Google Photos uses Semi - Supervised ML to determine which person is within the photo. 

# Reinforcement 
uses an agent which can observe the environment and preform actions, depending on the action there will be a reward/punishment given out to the Agent. This will establish a policy in which the agent operates.

An example is DeepMind's AlphaGo program, which beat champion Ke Jie at the game of Go. 


# Batch
