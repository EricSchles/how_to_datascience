##Business phases

These phases should be followed in order from top to bottom.

Domain expertise

- This is the idea of knowing your domain, understanding it fully.  Asking good questions about your industry and then translating those question into a machine learing, data science or technical context to provide a solution or some form of value.

-One machine learning, or data science thing you might do in this phase is data cleaning.  Another very basic machine learning technique is "data discovery".  This is done with clustering and partitioning algorithms, to understand the natural clusters of your data.  Examples include:

- k-means
- k-nearest-neighbors
- (advanced) hdbscan

Simple Machine learning

These are your parismonious (easy to understand, easy to use to gain value from) models.  Examples include:

* linear regression (with ordinary least squares)
* decision trees
* probabilistic graphic models (PGMs)

Advanced Machine learning

These are your complex and maybe even hard to use correctly models.  But they are powerful and usually very good at making predictions.  Examples include:

* support vector machines
* neural networks
* anything that's not simple because there are literally thousands of these

##Academic phases

Statistics (the basics of machine learning)

-start with a course on simple linear regression and some probability 
-then take a course in multivariate linear regression
-then take a course in time series - here is where you'll start to be able to solve lots of problems and then can move to using simple machine learning algorithms in the business context.

Simple machine learning

-bayesian statistics is sort of the the next place to go - here you'll learn about naive bayesian classifiers and how to classify data
-a course on probabilistic graphical models makes sense
-a course on decision trees, k-means clustering, and other simple machine learning algorithms (read scikit learn documentation)

Advanced machine learning

Cautionary note: there be dragons here
-a course on neural networks
-a course on big data algorithms (look at dask documentation or tensorflow under the hood)
-information theory
-theory of computation

##Aside

You could use a neural network to tune your hyper parameter for k-means or k-nearest-neighbors to get the "right" number of clusters.

