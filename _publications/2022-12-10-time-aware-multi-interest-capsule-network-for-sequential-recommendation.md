---
title: "Time-aware Multi-interest Capsule Network for Sequential Recommendation"
collection: publications
permalink: /publication/2022-12-10-time-aware-multi-interest-capsule-network-for-sequential-recommendation
date: 2022-12-10
venue: 'SDM 2022'
citation: 'Zhikai, W. Yanyan, S. (2022). "Time-aware Multi-interest Capsule Network for Sequential Recommendation" <i>SDM 2022</i>. 1(3).'
---
![sdm]({{site.url}}/images/sdm.png)

3. [link](https://epubs.siam.org/doi/abs/10.1137/1.9781611977172.63)  [pdf]({{site.url}}/files/sdm.pdf)

   **Zhikai Wang**,Yanyan Shen

   *SDM2022 (accept rate: 28.7%)*
   
   **Abstract**: In recent years, sequential recommendation has been widely researched, which aims to predict the next item of interest based on user's previously interacted item sequence. Many works use RNN to model the user interest evolution over time. However, they typically compute a single vector as the user representation, which is insufficient to capture the variation of user diverse interests. Some non-RNN models employ the dynamic routing mechanism to automatically vote out multiple capsules that represent user's diverse interests, but they are ignorant of the temporal information of user's historical behaviors, thus yielding suboptimal performance. 
   In this paper, we aim to establish a time-aware dynamic routing algorithm to effectively extract temporal user multiple interests for sequential recommendation. We observe that the significance of an item to user interests may change monotonically over time, and user interests may fluctuate periodically. Following the intuitive temporal patterns of user interests, we propose a novel time-aware multi-interest capsule network named TAMIC that leverages two kinds of time-aware voting gates, i.e., monotonic gates and periodic gates, to control the influence of each interacted item on user's current interests during the routing procedure. We further employ an aggregation module to form a temporal multi-interest user representation which is used for next item prediction. Extensive experiments on real-world datasets verify the effectiveness of the time gates and the superior performance of our TAMIC approach on sequential recommendation, compared with the state-of-the-art methods.