---
title: "Feature Staleness Aware Incremental Learning for CTR prediction"
collection: publications
permalink: /publication/2023-4-19-feature-staleness-aware-incremental-learning-for-ctr-prediction
date: 2023-4-19
venue: 'IJCAI 2023'
citation: 'Zhikai, W. Yanyan, S. Zibin, Z. and Kangyi, L. (2023). "Feature Staleness Aware Incremental Learning for CTR prediction" <i>IJCAI 2023</i>. 1(2).'
---
![ijcai]({{site.url}}/images/ijcai.png)
[pdf]({{site.url}}/files/ijcai23.pdf)

   **Zhikai Wang**,Yanyan Shen, Zibin Zhang, Kangyi Lin

   *IJCAI2023 (accept rate: 15%)*

   **Abstract**: Click-through Rate (CTR) prediction in real-world recommender systems often deals with billions of user interactions every day. To improve the training efficiency, it is common to update the CTR prediction model incrementally using the new incremental data and a subset of historical data. However, the feature embeddings of a CTR prediction model often get stale when the corresponding features do not appear in current incremental data. In the next period, the model would have a performance degradation on samples containing stale features, which we call the feature staleness problem. To mitigate this problem, we propose a Feature Staleness Aware Incremental Learning method for CTR prediction (FeSAIL) which adaptively replays samples containing stale features. We first introduce a staleness-aware sampling algorithm (SAS) to sample a fixed number of stale samples with high sampling efficiency. We then introduce a staleness-aware regularization mechanism (SAR) for a fine-grained control of the feature embedding updating. We instantiate FeSAIL with a general deep learning-based CTR prediction model and the experimental results demonstrate FeSAIL outperforms various state-of-the-art methods on four benchmark datasets.