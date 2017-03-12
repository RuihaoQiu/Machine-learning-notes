# Machine learning notes
This is a very personal notes of machine learning study, recording my understanding on various topics, methods and ideas.

# Basic concepts
## Supervised learning
### Classification
Assume that we have a set of labeled examples with different features. We would like to find a good way to separate the examples with certain features.This classification can be used to predict new properties of unknow data. _e.g._ cat and tiger -- size, color, sound, ... 

- **Decision surface/boundary:** the surface that well separate given data.

Models:
1. **Nearest neighbor -- _k_NN**  
Pick up a certain point, count _k_ nearest neighbors, this point will be assigned to the classification of the majority. Only one parameter to be considered, **_k_ - the number of neighbors**.  
**Optimize _k_:**  
Small _k_, non-smooth decision boundary, higher accuracy but lower interpretability;  
large _k_, smooth decision boundary, lower accuracy but higher interpretability.

2. **Naive Bayes**  
**Bayes’ Theorem** - Obtain the posterior possibility from the prior, through the formula P(C|x) = P(x|C) * P(C) / P(x), for multi-feature case, P(C|x) = P(C)P(x1|C)P(x2|C)...P(xn|C)/P(x).  
For a given testing dataset, calculate the posterior possibility of each class, assign this dataset to the class with largest posterior possibility.
The prior possibilities can be estimated from Gaussian distribution parameterized by the mean and variance of each class.

3. **Support vector machine -- SVM**

4. **Decision tree**

### Regression
The output variables are continous. _e.g._ height -- weight
## Unsupervised learning
Examples without labels. _e.g._ credit default of bank customers
### Clustering
Discover groups of similar examples.  

