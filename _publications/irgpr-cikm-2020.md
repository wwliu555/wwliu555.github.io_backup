---
title: "Personalized Re-ranking with Item Relationships for E-commerce"
collection: publications
category: conferences
permalink: /publication/irgpr-cikm-2020
excerpt: '**Weiwen Liu**, Qing Liu, Ruiming Tang, Junyang Chen, Xiuqiang He, Pheng Ann Heng'
date: 2020-10-19
venue: 'Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM 2020)'
paperurl: 'https://dl.acm.org/doi/10.1145/3340531.3412332'

---

Re-ranking is a critical task for large-scale commercial recommender systems. Given the initial ranked lists, top candidates are re-ranked to improve the accuracy of the ranking results. However, existing re-ranking strategies are sub-optimal due to (i) most prior works do not consider explicit item relationships, like being substitutable or complementary, which may mutually influence the user satisfaction on other items in the lists, and (ii) they usually apply an identical re-ranking strategy for all users, with personalized user preferences and intents ignored. To resolve the problem, we construct a heterogeneous graph to fuse the initial scoring information and item relationships information. We develop a graph neural network based framework, IRGPR, to explicitly model transitive item relationships by recursively aggregating relational information from multi-hop neighborhoods. We also incorporate a novel intent embedding network to embed personalized user intents into the propagation. We conduct extensive experiments on real-world datasets, demonstrating the effectiveness of IRGPR in re-ranking. Further analysis reveals that modeling the item relationships and personalized intents are particularly useful for improving the performance of re-ranking.