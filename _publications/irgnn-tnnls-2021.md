---
title: "Item Relationship Graph Neural Networks for E-commerce"
collection: publications
category: manuscripts
permalink: /publication/irgnn-tnnls-2021
excerpt: '**Weiwen Liu**, Yin Zhang, Jianling Wang, Yun He, James Caverlee, Patrick PK Chan, Daniel S Yeung, Pheng-Ann Heng'
date: 2021-03-08
venue: 'IEEE Transactions on Neural Networks and Learning Systems (TNNLS 2021)'
paperurl: 'https://people.engr.tamu.edu/caverlee/pubs/IRGNN-TNNLS2021.pdf'
---

In a modern e-commerce recommender system, it is important to understand the relationships among products. Recognizing product relationships—such as complements or substitutes—accurately is an essential task for generating better recommendation results, as well as improving explainability in recommendation. Products and their associated relationships naturally form a product graph, yet existing efforts do not fully exploit the product graph’s topological structure. They usually only consider the information from directly connected products. In fact, the connectivity of products a few hops away also contains rich semantics and could be utilized for improved relationship prediction. In this work, we formulate the problem as a multilabel link prediction task and propose a novel graph neural network-based framework, item relationship graph neural network (IRGNN), for discovering multiple complex relationships simultaneously. We incorporate multihop relationships of products by recursively updating node embeddings using the messages from their neighbors. An edge relational network is designed to effectively capture relational information between products. Extensive experiments are conducted on real-world product data, validating the effectiveness of IRGNN, especially on large and sparse product graphs.