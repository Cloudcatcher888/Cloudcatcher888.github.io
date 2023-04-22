---
title: "Incremental Learning for Multi-interest Sequential Recommendation"
collection: publications
permalink: /publication/2023-4-22-incremental-learning-for-multi-interest-sequential-recommendation
date: 2023-4-22
venue: 'ICDE 2023'
citation: 'Zhikai, W. (2023). "Incremental Learning for Multi-interest Sequential Recommendation." <i>ICDE 2023</i>. 1(1).'
---
<div align=center><img width = '650' height ='250' src ="images/icde2.png"/></div>

[pdf]({{site.url}}/files/icde.pdf) [slides]({{site.url}}/files/icde_slides.pdf) 

   **Zhikai Wang**,Yanyan Shen

   *ICDE2023 (**best paper award**, accept rate: 19.3%)*

   **Abstract**: In recent years, sequential recommendation has been widely researched, which aims to predict the next item of interest based on user's previously interacted item sequence. Existing works utilize capsule network and self-attention method to explicitly capture multiple underlying interests from a user's interaction sequence, achieving the state-of-the-art sequential recommendation performance. In practice, the lengths of user interaction sequences are ever-increasing and users might develop new interests from new interactions, and a model should be updated or even expanded continuously to capture the new user interests. We refer to this problem as incremental multi-interest sequential recommendation, which has not yet been well investigated in existing literature. In this paper, we propose an effective incremental learning framework of multi-interest sequential recommendation called IMSR, which augments the traditional fine-tuning strategy with the existing-interests retainer (EIR), new-interests detector (NID), and projection-based interests trimmer (PIT) to adaptively expand the model to accommodate user's new interests and prevent it from forgetting user's existing interests. Extensive experiments on real-world datasets verify the effectiveness of the proposed IMSR on incremental multi-interest sequential recommendation, compared with various baseline approaches.