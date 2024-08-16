---
title: "A Framework for Elastic Adaptation of User Multiple Intents in Sequential Recommendation"
collection: publications
permalink: /publication/2024-01-01-a-framework-for-elastic-adaptation-of-user-multiple-intents-in-sequential-recommendation
date: 2024-01-01
venue: 'TKDE'
citation: 'Zhikai Wang, Yanyan Shen. <i>TKDE</i>.'
---
   **Zhikai Wang**,Yanyan Shen

   **Abstract**: Recently, substantial research has been conducted on sequential recommendation, with the objective of forecasting the subsequent item by leveraging a user’s historical sequence of interacted items. Prior studies employ both capsule networks and self-attention techniques to effectively capture diverse underlying intents within a user’s interaction sequence, thereby achieving the most advanced performance in sequential recommendation. However, users could potentially form novel intents from fresh interactions as the lengths of user interaction sequences grow. Consequently, models need to be continually updated or even extended to adeptly encompass these emerging user intents, referred as incremental multi-intent sequential recommendation. In this paper, we propose an effective **I**ncremental learning framework for user **M**ulti-intent **A**daptation in sequential recommendation called IMA, which augments the traditional fine-tuning strategy with the existing-intents retainer, new-intents detector, and projection-based intents trimmer to adaptively expand the model to accommodate user’s new intents and prevent it from forgetting user’s existing intents. Furthermore, we upgrade the IMA into an **E**lastic **M**ulti-intent **A**daptation (EMA) framework which can elastically remove inactive intents and compress user intent vectors under memory space limit. Extensive experiments on real-world datasets verify the effectiveness of the proposed IMA and EMA on incremental multi-intent sequential recommendation, compared with various baselines.
