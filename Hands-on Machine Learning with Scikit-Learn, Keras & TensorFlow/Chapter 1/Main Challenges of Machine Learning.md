# Insufficent Quantity of Training Data
In the article "The Unreasonable effectiveness of Data", it showed that simple aglorithms preformed just as good as more complex alogorithms once they were fed enough data. It is important to note that pros and cons of algorithm development vs corpos developement. 

# Nonrepresentative Training Data
It is important to have training data that represents new cases you want to generalize to. This is important espically for algorithms which are sensative to noise, as this kinda change how the model will predict depending on the missing data. 

It is crucial to use a training set that is representative of the cases you want to generalize to. This is harder than it sounds, if the sample is too small, you will have **sampling noise**. But even very large samples, can be nonrepresentative if the sampling method is flawed, which results in **sampling bias**

# Poor-Quality Data
If the data is poor quality and full of errors, or outliers, this can cause alot of issues when feeding it into the ML algorithm. It is often well worth the effort to clean up the taining data. Most data scientist, spend a significant part of their time just doing that. 

Outliers, Missing features, Missing values are just some examples which can affect quality. 

# Irrelevant Features
 Garbage in = Garbage out, it is important to just focus on relevant features, the process in which you select relevant features to train the model is called **feature engineering**.
 - Feature selection (selecting the most useful features to train on among exisiting features)
 - Feature extraction (combining exisiting features to produce a more useful one aka dimensionality reduction algorithms)
 - Creating new features by gathering new data. 

# Overfitting the Training Data
This means your model preforms well on training data but it does not generalize well.  If the training set is too noisy or too small ( which introduces smapling noise), the model is likely to detect patterns within the noise itself.

Overfitting happens when the model is too complex relative to the amount and noiseness of thet training data.  Some solutions are:

- Simplify the model, reduce the number of attributes in the training data, or by constraining the model to a simplier one. i.e. Linear model rather than a high-degree polynomial. 

- Gather more training data. 

- Reduce the noise in training data 

Constraining a model to make it simplier and reduce the risk of overfitting is called **regularization** 

**Degrees of freedom** is something we want to minimize to allow for regularization to take place. We can constrain one feature to force a small