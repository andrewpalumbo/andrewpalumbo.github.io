---
title: Mahout Features by Engine:
---
***Mahout 1.0 Features by Engine***

| | Single Machine | [MapReduce](http://hadoop.apache.org/docs/r1.2.1/mapred_tutorial.html)| [Spark](https://spark.apache.org/) | [H2O](http://0xdata.com/) | [Flink](https://flink.incubator.apache.org/)
---------------------------------------------|:----------------:|:-----------:|:------:|:---:|:----:|
**Mahout Scala DSL**| 
|   [Mahout Distributed BLAS. Distributed Row Matrix API with R and Matlab like operators. Distributed ALS, SPCA, SSVD, thin-QR. Similarity Analysis](http://mahout.apache.org/users/sparkbindings/home.html).    | |  | [x](https://mahout.apache.org/users/sparkbindings/ScalaSparkBindings.pdf) | [x](https://github.com/apache/mahout/tree/master/h2o) |[*in development*](https://github.com/tillrohrmann/mahout/tree/flink-bindings/flink)|
||
**Mahout Interactive Shell**| 
|   [Interactive REPL shell for Spark optimized Mahout DSL](http://mahout.apache.org/users/sparkbindings/play-with-shell.html) | | | x |
||
**CLI Based Collabritive Filtering**|
    User-Based Collaborative Filtering           | x |  |[x](https://github.com/apache/mahout/blob/master/spark/src/test/scala/org/apache/mahout/drivers/RowSimilarityDriverSuite.scala)
    Item-Based Collaborative Filtering           | x | [x](https://mahout.apache.org/users/recommender/intro-itembased-hadoop.html) | [x](https://mahout.apache.org/users/recommender/intro-cooccurrence-spark.html) |
    Matrix Factorization with ALS | x | [x](https://mahout.apache.org/users/recommender/intro-als-hadoop.html) |  |
    Matrix Factorization with ALS on Implicit Feedback | x | [x](https://mahout.apache.org/users/recommender/intro-als-hadoop.html) |  |
    Weighted Matrix Factorization, SVD++  | x | | 
||
**CLI Based Classification**| | |
    Logistic Regression - trained via SGD   | [x](http://mahout.apache.org/users/classification/logistic-regression.html) |
    Naive Bayes / Complementary Naive Bayes  | | [x](https://mahout.apache.org/users/classification/bayesian.html) | [*in development*](https://issues.apache.org/jira/browse/MAHOUT-1493) |  *in development*
    Random Forest | | [x](https://mahout.apache.org/users/classification/partial-implementation.html)|
    Hidden Markov Models - single machine  | [x](https://mahout.apache.org/users/classification/hidden-markov-models.html) |
    Multilayer Perceptron - single machine | x |
||
**CLI Based Clustering**||
    Canopy Clustering  | [*deprecated*](https://mahout.apache.org/users/clustering/canopy-clustering.html) | [*deprecated*](https://mahout.apache.org/users/clustering/canopy-clustering.html)| 
    k-Means Clustering   | [x](https://mahout.apache.org/users/clustering/k-means-clustering.html) | [x](https://mahout.apache.org/users/clustering/k-means-clustering.html) |  
    Fuzzy k-Means   | [x](https://mahout.apache.org/users/clustering/fuzzy-k-means.html) | [x](https://mahout.apache.org/users/clustering/fuzzy-k-means.html)|  
    Streaming k-Means   | [x](https://mahout.apache.org/users/clustering/streaming-k-means.html) | [x](https://mahout.apache.org/users/clustering/streaming-k-means.html) |  
    Spectral Clustering   |  | [x](https://mahout.apache.org/users/clustering/spectral-clustering.html) |  
||
**CLI Based Dimensionality Reduction**- note: most dimensionality reduction algorithms
 are available through the [DSL for all engines](https://mahout.apache.org/users/sparkbindings/home.html)||
    Singular Value Decomposition | x | x | |
    Lanczos Algorithm  | x | x | 
    Stochastic SVD  | [x](https://mahout.apache.org/users/dim-reduction/ssvd.html) | [x](https://mahout.apache.org/users/dim-reduction/ssvd.html) |  |
    PCA (via Stochastic SVD) | x | x |  |
    QR Decomposition         | x | x |  |
||
**Topic Models**||
    Latent Dirichlet Allocation  | x | x |
||
**Miscellaneous**||
    RowSimilarityJob   |  | x | [x](https://github.com/apache/mahout/blob/master/spark/src/test/scala/org/apache/mahout/drivers/RowSimilarityDriverSuite.scala) | 
    ConcatMatrices  |  | x |
    Collocations  |  | [x](https://mahout.apache.org/users/basics/collocations.html) |  
    Sparse TF-IDF Vectors from Text |  | [x](https://mahout.apache.org/users/basics/creating-vectors-from-text.html) |
    XML Parsing|  | [x](https://issues.apache.org/jira/browse/MAHOUT-1479?jql=text%20~%20%22wikipedia%20mahout%22) |
    Email Archive Parsing |  | [x](https://github.com/apache/mahout/tree/master/integration/src/main/java/org/apache/mahout/text) | 
    Lucene Integration |  | [x](https://mahout.apache.org/users/basics/creating-vectors-from-text.html) |
    Evolutionary Processes | [x](https://github.com/apache/mahout/tree/master/mrlegacy/src/main/java/org/apache/mahout/ep) |
    



