---
title: "Toolace: Winning the Points of LLM Function Calling"
collection: publications
category: conferences
permalink: /publication/toolace-iclr-2025
excerpt: '**Weiwen Liu**\*, Xu Huang\*, Xingshan Zeng\*, Xinlong Hao, Shuai Yu, Dexun Li, Shuai Wang et al.'
date: 2025-04-24
venue: 'The 13th International Conference on Learning Representations (ICLR 2025)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2409.00920'
# citation: 'Weiwen Liu, Xu Huang, Xingshan Zeng, Xinlong Hao, Shuai Yu, Dexun Li, Shuai Wang et al. "Toolace: Winning the points of llm function calling." arXiv preprint arXiv:2409.00920 (2024).'
---

  Function calling significantly extends the application boundary of large language models (LLMs), where high-quality and diverse training data is critical for unlocking this capability. However, collecting and annotating real function-calling data is challenging, while synthetic data from existing pipelines often lack coverage and accuracy. In this paper, we present ToolACE, an automatic agentic pipeline designed to generate accurate, complex, and diverse tool-learning data, specifically tailored to the capabilities of LLMs. ToolACE leverages a novel self-evolution synthesis process to curate a comprehensive API pool of 26,507 diverse APIs. Dialogs are further generated through the interplay among multiple agents, under the guidance of a complexity evaluator. To ensure data accuracy, we implement a dual-layer verification system combining rule-based and model-based checks. We demonstrate that models trained on our synthesized data---even with only 8B parameters---achieve state-of-the-art performance, comparable to the latest GPT-4 models. Our model and a subset of the data are publicly available at [https://huggingface.co/Team-ACE](https://huggingface.co/Team-ACE).