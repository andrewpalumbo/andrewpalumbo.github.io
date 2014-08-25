---
title: Mahout Features by Engine:
---
|                    | Single Machine | MapReduce | Spark | h2o 
---------------------------------------------|:----------------:|:-----------:|:------:|:---:|
**Mahout DSL**| | | x | *in dev*|
||
**Collaborative Filtering**|
User-Based Collaborative Filtering           | x |
Item-Based Collaborative Filtering           | x | x | x |
Matrix Factorization with ALS | x | x | x |
Matrix Factorization with ALS on Implicit Feedback | x | x | x |
Weighted Matrix Factorization, SVD++, Parallel SGD  | x |
||
**Classification**| | |
 Spark Logistic Regression - trained via SGD   | x |
    Naive Bayes/ Complementary Naive Bayes  | | x | *in dev* |
    Random Forest | | x|
    Hidden Markov Models - single machine  | x |
    Multilayer Perceptron - single machine | x |
||
**Clustering**||
    Canopy Clustering  | *deprecated* | *deprecated*| 
    k-Means Clustering   | x | x |  
    Fuzzy k-Means   | x | x |  
    Streaming k-Means   | x | x |  
    Spectral Clustering   |  | x |  
||
**Dimensionality Reduction**||
    Singular Value Decomposition | x | 
    Lanczos Algorithm  | x | x | 
    Stochastic SVD  | x | x | x |
    Principal Component Analysis (via Stochastic SVD) | x | x |
||
**Topic Models**||
    Latent Dirichlet Allocation  | x | x |
||
**Miscellaneous**||
    Frequent Pattern Mining  |  | *deprecated* |
    RowSimilarityJob - compute pairwise similarities between the rows of a matrix  |  | x | 
    ConcatMatrices - combine 2 matrices or vectors into a single matrix |  | x |
    Collocations - find co-locations of tokens in text |  | x |
    Sparse TF-IDF vectorsfrom Text |  | x |
    XML Splitting|  | x |
    Email Archive Parser |  | x | 



