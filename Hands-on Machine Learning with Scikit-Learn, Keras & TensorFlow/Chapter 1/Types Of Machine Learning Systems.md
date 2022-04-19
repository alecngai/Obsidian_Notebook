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
In Batch Learning the system is incapable of learning incrementally, it is trained using all available data, then launched into production and runs without learning anymore. This is done offline as it is computational demanding, this is  called offline learning. 

To retrain a batch system, you must compile a new data set with new data and old and retrain the system, then stop the old system and launch the new one. Simply update the database and train a new version of the system and re-upload. 

Batch learning is computationally demanding so to retrain on the entire dataset can only be done daily or weekly depending on the dataset,, so it is not a useful system for time sensitive problems. 

# Online
In online learning the system is trained incrementally by feeding it data instances sequentially, individually or in small groups called mini-batches. This is good for systems that needed new live data, i.e. stock market predictions and analysis. Saves on memory since once the system is trained on new data instances it does not need them anymore and can be discarded. 

It is importat to monitor the quality of data, if there is bad data fed into the system the preforamnce will drop, it is important to know when to turn off learning to maintain the system preformance. 

# Out-of-core 
With systems that have huge data sets that cannot fit on the machine, The algorithm loads part of the data, runs a training step on that data and repeats until it processes all the data. Usually this is done offline, it is also known as incremental learning. 

###### Learning rate
How fast the system adapts to changing data, if high learning rate, the system will rapidly adapt to new data, but also quickly forget the old data. This is not useful for spam filter as you must filter out not only newest spam but also the oldest too.

Low learning rate, system will have more inertia, will learn more slowly but be less sensitive to noise in new data or to sequences of non-representative data points, outliers and anomalies. 

# Instance-Based 
Measure of similarity, is a way to confirm between two instances and act upon them, for example spam emails will be flagged if there is a % similarity between the two. 

System learns the examples by heart, then generalizes to new cases using a similarty measure to compare them together. 

# Model-Based
Another way to generalize from a set of examples is to build a model, using this model we use this to predict which the instance will be compared too. 