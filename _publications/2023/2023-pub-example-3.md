---
title:          "Unveiling Latent Causal Rules: A Temporal Point Process Approach for Abnormal Event Explanation"
date:           2023-01-22 00:01:00 +0800
selected:       false
pub:            "The International Conference on Artificial Intelligence and Statistics (AISTATS)"
pub_date:       "2023"
# semantic_scholar_id: 11ac0b5634a282f1a0da204b98e7473d8b480dfb  # use this to retrieve citation count
abstract: >-
  In high-stakes systems such as healthcare, it is critical to understand the causal reasons behind unusual events, such as sudden changes in patient’s health. Unveiling the causal reasons helps with quick diagnoses and precise treatment planning. In this paper, we propose an automated method for uncovering “if-then” logic rules to explain observational events. We introduce temporal point processes to model the events of interest, and discover the set of latent rules to explain the occurrence of events. To achieve this goal, we employ an Expectation-Maximization (EM) algorithm. In the E-step, we calculate the posterior probability of each event being explained by each discovered rule. In the M-step, we update both the rule set and model parameters to enhance the likelihood function’s lower bound. Notably, we will optimize the rule set in a differential manner. Our approach demonstrates accurate performance in both discovering rules and identifying root causes. We showcase its promising results using synthetic and real healthcare datasets.

cover:          /assets/images/covers/Unveiling.png
authors:
  - Yiling Kuang *
  - Chao Yang *
  - Yang Yang
  - Shuang Li
links:
  Paper: https://proceedings.mlr.press/v238/kuang24a/kuang24a.pdf
  # Code: https://github.com
  # Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---
