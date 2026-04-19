---
title:          "Reinforcement Logic Rule Learning for Temporal Point Processes"
date:           2023-01-1 00:01:00 +0800
selected:       false
pub:            "ICML 2022 Workshop (IMLH 2022)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"

abstract: >-
  We propose a framework that can incrementally expand the explanatory temporal logic rule set to explain the occurrence of temporal events. Leveraging the temporal point process modeling and learning framework, the rule content and weights will be gradually optimized until the likelihood of the observational event sequences is optimal. The proposed algorithm alternates between a master problem, where the current rule set weights are updated, and a subproblem, where a new rule is searched and included to best increase the likelihood. The formulated master problem is convex and relatively easy to solve using continuous optimization, whereas the subproblem requires searching the huge combinatorial rule predicate and relationship space. To tackle this challenge, we propose a neural search policy to learn to generate the new rule content as a sequence of actions. The policy parameters will be trained end-to-end using the reinforcement learning framework, where the reward signals can be efficiently queried by evaluating the subproblem objective. The trained policy can be used to generate new rules in a controllable way. We evaluate our methods on both synthetic and real healthcare datasets, obtaining promising results.
cover:          /assets/images/covers/RL-TPP-Rule.png
authors:
  - Chao Yang
  - Lu Wang
  - Kun Gao
  - Shuang Li
links:
  Paper: https://arxiv.org/pdf/2308.06094
  # Code: https://github.com/luost26/bubble-visual-hash
  # Demo: https://luost26.github.io/bubble-visual-hash
---
