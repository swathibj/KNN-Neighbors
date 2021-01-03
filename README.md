# KNN Neighbors Project Exercise 

* Created machine learning model capable of detecting the difference between a rock or a mine based on the response of the 60 separate sonar frequencies.
* Due to the simplicity of KNN for Classification, focused on using a PipeLine and a GridSearchCV tool, since these skills can be generalized for any model.

# Code and Resources Used

* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn.
* Data Source: https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)

# About Data:

## The Sonar Data:

* Detecting a Rock or a Mine Sonar (sound navigation ranging) is a technique that uses sound propagation (usually underwater, as in submarine navigation) to 
  navigate, communicate with or detect objects on or under the surface of the water, such as other vessels.
* The data set contains the response metrics for 60 separate sonar frequencies sent out against a known mine field (and known rocks).
* These frequencies are then labeled with the known object they were beaming the sound at (either a rock or a mine).

# Data Cleaning:

* As data is already in usable format, so no cleaning process is followed here.

# EDA

# Model Building
First, split the data into train and tests sets with a test size of 10%.

I tried KNN Neighbors models and evaluated them using Acuuracy_Score, Precision and Recall. 
I chose these because it is relatively easy to interpret and easily understandable.

# Model performance
The KNN Neighbors model has below performace metrics.

* Accuracy_Score : 0.90
* Precision : 0.92
* Recall : 0.92
