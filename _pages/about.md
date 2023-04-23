---
permalink: /
title: "Zhikai Wang - SJTU"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Education
======
* Sept. 2019-Present, PhD candidate (graduate in June 2024) @ [Data Driven Software Technology Lab](https://ddst.sjtu.edu.cn), [Department of Computer Science and Engineering](https://www.cs.sjtu.edu.cn/), [Shanghai Jiao Tong University, Shanghai, China 200240](https://www.sjtu.edu.cn/)
supervised by [Prof. Yanyan Shen](https://www.cs.sjtu.edu.cn/~shen-yy/). 

* Sept. 2015-July 2019, Bachelor of Engineering at Shanghai Jiao Tong University. 

Work experience
======
* Dec. 2021-Dec. 2022: Research Assistant in Tencent, supervised by Zibin Zhang and Kangyi Lin.
  * We study incremental learning for CTR prediction by resampling data with features which have not been updated for a while. We deployed our feature staleness aware CTR prediction method on Wechat Official Accounts Platform and achieved prominent improvements in A/B test.

News
======
* 2023.03: Our paper “Incremental Learning for Multi-interest Sequential Recommendation” received the
ICDE 2023 <font color="red">Best Paper Award (top 1)</font>!

Research Interest
======
I'm interested in devleoping efficient models for recommendation system (e.g. CTR prediction and sequential recommendation) and improve the generalization ability of models in incremental scenario.  

Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
