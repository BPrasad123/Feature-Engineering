# Topic: Feature Engineering #

Feature Engineering is a very important part of Machine Learning exercise. There are a number of sub-topics under this section
and we will high-light on important and useful techniques that can be leveraged to accomplish better result.


# Feature Scaling #
It is technique to counteract the effect of different features having different scales or ranges of thier corresponding values. Idea is to bring all the features onto the same scale while maintaining the integrity.

## 1. General Undestanding: ##
There are two types of scaling -
1. Normalization (Also called as Min-Max scaling): To fit the range of a series in between 0 and 1. It is independent of the type of data distribution. Once normalization is done, it can be multipled by m so as to make the range 0 to m, if needed.  
Application:
- Normalize pixel intesities to fit into a range of 0 and 255  
- Neural Network algorithm wants data in the range of 0 to 1.  
2. Standardization (also called as Z-score normalization): Assumption is that data is more or less normally distributed, that is Gaussian distribution. It does the scaling so as to make the mean as 0 and standard deviation as 1. It might lead to unwanted result if applied on non-Gaussian distributed data.  
Application:
- Clustering algorithm  
- Principal Component Analysis  
 Disclaimer: I am still working on my research on this and will share my findings and code shortly.


*Reference Links:*  
https://stats.stackexchange.com/a/264097  
http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf
http://sebastianraschka.com/Articles/2014_about_feature_scaling.html


## 2. Dimensionality Reduction ##
Principal Component Analysis, Singular Value Decomposition and Sammon’s Mapping.  

## 3. Feature Selection ##
### I. Filter Methods ###
Chi squared test, information gain and correlation coefficient scores.  
### II. Wrapper Methods ###
Recursive feature elimination algorithm, Backward Elimination  
### III. Embedded Methods ###
Regularization algorithms are the LASSO, Elastic Net and Ridge Regression  


# NLP #
## Embedding ##
https://www.quora.com/What-does-the-word-embedding-mean-in-the-context-of-Machine-Learning#  
https://www.linkedin.com/feed/update/urn:li:activity:6414655628450631680  


## RESEARCH ##
1. Categorial to one hot is not all the time good option being computationally expensive  
2. Linear Regression to feed into GBM to reduce dimension for categorical values  
3. Use embedding in place of one hot to reduce dimension  
