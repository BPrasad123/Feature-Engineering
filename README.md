# Topic: Feature Engineering

Feature Engineering is a very important part of Machine Learning exercise. There are a number of sub-topics under this section
and we will high-light on important and useful techniques that can be leveraged to accomplish better result.


# Feature Scaling
It is technique to counteract the effect of different features having different scales or ranges of thier corresponding values.
Idea is to bring all the features onto the same scale while maintaining the integrity.

General Undestanding:
  There are two types of scaling -
    Normalization: To fit the range of a series in between 0 and 1. It is independent of the type of data distribution.
                   Once normalization is done, it can be multipled by m so as to make the range 0 to m, if needed.
    Standardization: Assumption is that data is more or less normally distributed, that is Gaussian distribution.
                     It does the scaling so as to make the mean as 0 and standard deviation as 1.
                     It might lead to unwanted result if applied on non-Gaussian distributed data.
 
 Disclaimer: I am still working on my research on this and will share my findings and code shortly.
