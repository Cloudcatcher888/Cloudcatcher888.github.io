---
title: "Relative Contrastive Learning for Sequential Recommendation
with Similarity-based Positive Pair Selection"
permalink: /publication/2024-07-16-relative-contrastive-learning-for-sequential-recommendation-with-similarity-based-positive-pair-selection
date: 2024-07-16
venue: 'CIKM (accept rate: 23.67%)'
citation: 'Zhikai Wang, Yanyan Shen, et al., in <i>CIKM 2024</i>.'
---
   **Zhikai Wang**, Yanyan Shen, et al.

   **Abstract**: Contrastive Learning (CL) enhances the training of sequential recommendation (SR) models through informative self-supervision signals. Existing methods often rely on data augmentation strategies to create positive samples and promote representation invariance. Some strategies such as item reordering and item substitution may inadvertently alter user intent. Supervised Contrastive Learning based methods find an alternative to augmentation-based CL methods by selecting same-target sequences (interaction sequences with the same target item) to form positive samples. However, SCL-based methods suffer from the scarcity of same-target sequences and consequently lack enough signals for contrastive learning. In this work, we propose to use similar sequences (with different target items) as additional positive samples and introduce a **R**elative **C**ontrastive **L**earning (RCL) framework for sequential recommendation. RCL comprises a dual-tiered positive sample selec tion module and a relative contrastive learning module. The former module selects same-target sequences as strong positive samples and selects similar sequences as weak positive samples. The latter module employs a weighted relative contrastive loss, ensuring that each sequence is represented closer to its strong positive samples than its weak positive samples. We apply RCL on two mainstream deep learning-based SR models, and our empirical results reveal that RCL can achieve 4.88% improvement averagely than the state-of the-art SR methods on five public datasets and one private dataset.The code can be found at https://github.com/Cloudcatcher888/RCL.
