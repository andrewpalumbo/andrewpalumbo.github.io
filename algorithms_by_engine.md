

Collaborative Filtering                    | Single Machine | MapReduce | Spark |
---------------------------------------------|:----------------:|:-----------:|:-------:|
User-Based Collaborative Filtering           | x |
Item-Based Collaborative Filtering           | x | x | x |
Matrix Factorization with Alternating Least Squares - single machine / MapReduce | x | x | x |
Matrix Factorization with Alternating Least Squares on Implicit Feedback | x | x | x |
Weighted Matrix Factorization, SVD++, Parallel SGD - | x |

Classification|Single Machine | MapReduce | Spark |
---------------------------------------------|:----------------:|:-----------:|:-------:|
    Logistic Regression - trained via SGD   | x |
    Naive Bayes/ Complementary Naive Bayes  | | x |
    Random Forest | | x|
    Hidden Markov Models - single machine  | x |
    Multilayer Perceptron - single machine | x |

Clustering|Single Machine | MapReduce | Spark |
---------------------------------------------|:----------------:|:-----------:|:-------:|
    Canopy Clustering  | deprecated | deprecated| 
    k-Means Clustering   | x | x |  
    Fuzzy k-Means   | x | x |  
    Streaming k-Means   | x | x |  
    Spectral Clustering   |  | x |  

Dimensionality Reduction|Single Machine | MapReduce | Spark |
---------------------------------------------|:----------------:|:-----------:|:-------:|
    Singular Value Decomposition | x | 
    Lanczos Algorithm  | x | x | 
    Stochastic SVD  | x | x | x |
    Principal Component Analysis (via Stochastic SVD) | x | x |

Topic Models|Single Machine | MapReduce | Spark |
---------------------------------------------|:----------------:|:-----------:|:-------:|
    Latent Dirichlet Allocation  | x | x |

Miscellaneous|Single Machine | MapReduce | Spark |
---------------------------------------------|:----------------:|:-----------:|:-------:|
    Frequent Pattern Mining  |  | deprecated |
    RowSimilarityJob - compute pairwise similarities between the rows of a matrix  |  | x | 
    ConcatMatrices - combine 2 matrices or vectors into a single matrix |  | x |
    Collocations - find co-locations of tokens in text |  | x |
    TF-IDF vectors from Text |  | x |
    XML Splitter  |  | x |
    Email Archive Parser |  | x | 


