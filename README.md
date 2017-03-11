# Machine learning notes
This is a very personal notes of machine learning study, recording my understanding on various topics, methods and ideas.

# Basic concepts
## Supervised learning
### Classification
Assume that we have a set of labeled examples with different features. We would like to find a good way to separate the examples with certain features.This classification can be used to predict new properties of unknow data. _e.g._ cat and tiger -- size, color, sound, ... 

- **Decision surface/boundary:** the surface that well separate given data.

Models:
1. **Nearest neighbor -- _k_NN**  
Pick up a certain point, count _k_ nearest neighbors, this point will be assigned to the classification of the majority. Only one parameter to be considered, **_k_ - the number of neighbors**. Small _k_, lower accuracy and higher interpretability.

2. **Naive Bayes**  
**Bayes’ Theorem** Obtain the posterior possibility from the prior, through the formula P(A|B) = P(B|A) * P(A) / P(B)


3. **Support vector machine -- SVM**
4. **Decision tree**

### Regression
The output variables are continous. _e.g._ height -- weight
## Unsupervised learning
Examples without labels. _e.g._ credit default of bank customers
### Clustering
Discover groups of similar examples.  

