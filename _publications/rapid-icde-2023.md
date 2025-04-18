---
title: "Personalized Diversification for Neural Re-ranking in Recommendation"
collection: publications
category: conferences
permalink: /publication/rapid-icde-2023
excerpt: '**Weiwen Liu**\*, Yunjia Xi\*, Jiarui Qin, Xinyi Dai, Ruiming Tang, Shuai Li, Weinan Zhang, Rui Zhang'
date: 2023-04-03
venue: 'IEEE 39th International Conference on Data Engineering (ICDE 2023)'
paperurl: 'https://www.ruizhang.info/publications/ICDE%202023%20Personalized%20Diversification%20for%20Neural%20Re-ranking%20in%20Recommendation.pdf'

---

Re-ranking, as the final stage of the multi-stage recommender systems (MRS), aims at modeling the listwise context and the cross-item interactions between the candidate items. The objective is usually the overall utility (e.g., total clicks or revenue) of the re-ranked list, which is determined not only by the relevance, but also by the diversity of the list. However, existing methods equally promote diversity for all users and often compromise the relevance ranking. In reality, users have different diversity preferences and we should diversify the list tailored to individual users’ interests and needs. Users’ behavior history contains rich information which may be used for inferring their diversity preferences, but has rarely been explored in existing work. In this work, we propose a novel neural re-ranking with personalized diversification method (dubbed RAPID) to address the above challenge. RAPID explicitly models each user’s preference distribution over different topics by exploiting the intra- and inter-topic interactions from the user’s behavior history. The personalized diversity gain brought by each candidate item is then measured by the item’s marginal diversity and the learned personalized preference. The relevance and the personalized diversity are jointly optimized in an end-to-end manner to automatically manage the relevance-diversity tradeoff. Experimental results on two public datasets and a proprietary dataset show that RAPID outperforms the state-of-the-art with the highest utility and the best relevance-diversity tradeoff. We further prove that RAPID has a regret bound of O(\sqrt(n)) on utility, which provides theoretical guarantee that its performance is near-optimal.