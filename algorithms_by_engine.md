---
title: Mahout Features by Engine:
---
|                    | Single Machine | MapReduce | Spark | h2o | Flink
---------------------------------------------|:----------------:|:-----------:|:------:|:---:|:----:|
**Mahout DSL**| | | x | *in development* |*in development*|
||
**Mahout Interactive Shell**| | | x |
||
**Collaborative Filtering**|
    User-Based Collaborative Filtering           | x |
    Item-Based Collaborative Filtering           | x | x | x |
    Matrix Factorization with ALS | x | x | x |
    Matrix Factorization with ALS on Implicit Feedback | x | x | *in development* |
    Weighted Matrix Factorization, SVD++, Parallel SGD  | x | | 
||
**Classification**| | |
    Logistic Regression - trained via SGD   | x |
    Naive Bayes/ Complementary Naive Bayes  | | x | *in development* |
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
    Singular Value Decomposition | x | x | x|
    Lanczos Algorithm  | x | x | 
    Stochastic SVD  | x | x | x |
    PCA (via Stochastic SVD) | x | x | x |
    QR Decomposition         | x | x | x |
||
**Topic Models**||
    Latent Dirichlet Allocation  | x | x |
||
**Miscellaneous**||
    Frequent Pattern Mining  |  | *deprecated* |
    RowSimilarityJob   |  | x | x | 
    ConcatMatrices  |  | x |
    Collocations  |  | x |  
    Sparse TF-IDF Vectors from Text |  | x |
    XML Parsing|  | x |
    Email Archive Parsing |  | x | 
    Lucene Integration |  | x |
    Evolutionary Process | x |
    



