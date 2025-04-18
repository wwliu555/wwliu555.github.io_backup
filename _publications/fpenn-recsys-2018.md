---
title: "Field-aware Probabilistic Embedding Neural Network for CTR Prediction"
collection: publications
category: conferences
permalink: /publication/fpenn-recsys-2018
excerpt: '**Weiwen Liu**, Ruiming Tang, Jiajin Li, Jinkai Yu, Huifeng Guo, Xiuqiang He, Shengyu Zhang'
date: 2018-09-27
venue: 'Proceedings of the 12th ACM Conference on Recommender Systems (RecSys 2018)'
paperurl: 'https://www.researchgate.net/profile/Weiwen-Liu-2/publication/327950889_Field-aware_probabilistic_embedding_neural_network_for_CTR_prediction/links/5c7d0c2892851c6950527cd6/Field-aware-probabilistic-embedding-neural-network-for-CTR-prediction.pdf'

---

For Click-Through Rate (CTR) prediction, Field-aware Factorization Machines (FFM) have exhibited great effectiveness by considering field information. However, it is also observed that FFM suffers from the overfitting problem in many practical scenarios. In this paper, we propose a Field-aware Probabilistic Embedding Neural Network (FPENN) model with both good generalization ability and high accuracy. FPENN estimates the probability distribution of the field-aware embedding rather than using the single point estimation (the maximum a posteriori estimation) to prevent overfitting. Both low-order and high-order feature interactions are considered to improve the accuracy. FPENN consists of three components, i.e., FPE component, Quadratic component and Deep component. FPE component outputs probabilistic embedding to the other two components, where various confidence levels for feature embeddings are incorporated to enhance the robustness and the accuracy. Quadratic component is designed for extracting low-order feature interactions, while Deep component aims at capturing high-order feature interactions. Experiments are conducted on two benchmark datasets, Avazu and Criteo. The results confirm that our model alleviates the overfitting problem while having a higher accuracy.