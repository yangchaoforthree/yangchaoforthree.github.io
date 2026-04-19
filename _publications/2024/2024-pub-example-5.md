---
title:          "Neuro-Symbolic Temporal Point Processes"
date:           2024-01-24 00:01:00 +0800
selected:       false
pub:            "The International Conference on Machine Learning (ICML)"
pub_date:       "2024"
# semantic_scholar_id: 11ac0b5634a282f1a0da204b98e7473d8b480dfb  # use this to retrieve citation count
abstract: >-
  Our goal is to efficiently discover a compact set of temporal logic rules to explain irregular events of interest. We introduce a neural-symbolic rule induction framework within the temporal point process model. The negative log-likelihood is the loss that guides the learning, where the explanatory logic rules and their weights are learned end-to-end in a differentiable way. Specifically, predicates and logic rules are represented as vector embeddings, where the predicate embeddings are fixed and the rule embeddings are trained via gradient descent to obtain the most appropriate compositional representations of the predicate embeddings. To make the rule learning process more efficient and flexible, we adopt a sequential covering algorithm, which progressively adds rules to the model and removes the event sequences that have been explained until all event sequences have been covered. All the found rules will be fed back to the models for a final rule embedding and weight refinement. Our approach showcases notable efficiency and accuracy across synthetic and real datasets, surpassing state-of-the-art baselines by a wide margin in terms of efficiency

cover:          /assets/images/covers/NSTPP.png
authors:
  - Yang Yang
  - Chao Yang
  - Boyang Li
  - Yinghao Fu
  - Shuang Li
links:
  Paper: https://arxiv.org/pdf/2406.03914?
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---
