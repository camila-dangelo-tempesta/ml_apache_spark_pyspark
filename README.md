# **Machine Learning with PySpark**

## Application of Machine Learning Algorithms: Linear Regression, Multiclass Classification, Binary Classification with Random Forest and PCA, Probabilistic Binary Classification with Naive Bayes and

The Apache Spark MLlib module contains the functions that implement Machine Learning
and was created to run in parallel, through a cluster, just like the other
Spark modules.

MLlib's Machine Learning (ML) algorithms can be run by all
programming languages supported by Spark as well as this module is interchangeable with
the other modules of the Spark framework.

The concept behind MLlib is simple. We can invoke ML algorithms and apply the
models in the RDDs. MLlib introduces some more data types like vectors and label points, which are functions
that we apply to the data set.

One of the important features about MLlib is that it contains only algorithms
of ML that can run in parallel across a cluster. Some classic algorithms
are not included in MLlib as they were not created for parallel processing. In
compensation, MLlib allows you to create models with some important algorithms such as Trees
of Decision and K-Means.

MLlib's algorithms are optimized for cluster computing and with large
data sets. If your goal is to apply ML to small or medium datasets,
probably MLlib will not be the best option for this.

Visit the official [MLlib documentation](https://spark.apache.org/docs/latest/ml-guide.html)

<div align="center">
<p float="left">
    <img src="/images/mllib.jpeg" width="1000" height="500"/>
</p>
</div>

***
## 1. BUSINESS PROBLEMS

The objective of this project is to bring a series of examples of creating Machine Learning models with PySpark, demonstrating in practice the entire Machine Learning pipeline for distributed environments and indicating characteristics, advantages, disadvantages and applications of some of the main learning algorithms of machine, in addition to addressing topics such as standardization, transformation of variables, dimensionality reduction with PCA and various data pre-processing tasks.

We will work with sample data and our focus will be on the Machine Learning process with Apache Spark.

***
## 2. BUSINESS ASSUMPTIONS

Algorithms used:

1. Linear Regression: prediction of automobile fuel consumption
2. Multiclass classification: prediction of the outcome of a football match
3. Binary Classification with Random Forest and PCA: prediction whether or not a customer will pay a bank loan
4. Probabilistic Binary Classification with Naive Bayes: prediction whether a text message is spam or not.

***
