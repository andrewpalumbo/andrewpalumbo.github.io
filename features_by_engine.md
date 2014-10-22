---
title: Mahout Features by Engine:
---
***Mahout 1.0 Features by Engine***

| | Single Machine | MapReduce | Spark | h2o | Flink
---------------------------------------------|:----------------:|:-----------:|:------:|:---:|:----:|
(**Mahout Scala DSL**)[http://mahout.apache.org/users/sparkbindings/home.html]| 
|   Mahout Distributed BLAS. Distributed Row Matrix API with R and Matlab like operators. Distributed ALS, SPCA, SSVD, thin-QR. Similarity Analysis.    | |  | x | x |*in development*|
||
**Mahout Interactive Shell**| 
|   Interactive REPL shell for Spark optimized Mahout DSL | | | x |
||
**CLI Based Collabritive Filtering**|
    User-Based Collaborative Filtering           | x |   | x |
    Item-Based Collaborative Filtering           | x | x | x |
    Matrix Factorization with ALS | x | x |  |
    Matrix Factorization with ALS on Implicit Feedback | x | x |  |
    Weighted Matrix Factorization, SVD++  | x | | 
||
**CLI Based Classification**| | |
    (Logistic Regression - trained via SGD)[http://mahout.apache.org/users/classification/logistic-regression.html]   | x |
    Naive Bayes / Complementary Naive Bayes  | | x | *in development* |  *in development*
    Random Forest | | x|
    Hidden Markov Models - single machine  | x |
    Multilayer Perceptron - single machine | x |
||
**CLI Based Clustering**||
    Canopy Clustering  | *deprecated* | *deprecated*| 
    k-Means Clustering   | x | x |  
    Fuzzy k-Means   | x | x |  
    Streaming k-Means   | x | x |  
    Spectral Clustering   |  | x |  
||
**CLI Based Dimensionality Reduction**||
    Singular Value Decomposition | x | x | |
    Lanczos Algorithm  | x | x | 
    Stochastic SVD  | x | x |  |
    PCA (via Stochastic SVD) | x | x |  |
    QR Decomposition         | x | x |  |
||
**Topic Models**||
    Latent Dirichlet Allocation  | x | x |
||
**Miscellaneous**||
    RowSimilarityJob   |  | x | x | 
    ConcatMatrices  |  | x |
    Collocations  |  | x |  
    Sparse TF-IDF Vectors from Text |  | x |
    XML Parsing|  | x |
    Email Archive Parsing |  | x | 
    Lucene Integration |  | x |
    Evolutionary Processes | x |
    



