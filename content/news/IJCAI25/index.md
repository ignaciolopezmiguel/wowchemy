---
title: Paper accepted at the International Joint Conference on Artificial Intelligence
subtitle: Rule-Guided Reinforcement Learning Policy Evaluation and Improvement

# Summary for listings and search engines
summary: Rule-Guided Reinforcement Learning Policy Evaluation and Improvement

# Link this post with a project
projects: []

# Date published
date: '2025-04-28T00:00:00Z'

# Date updated
date: '2025-04-28T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic
---

## Abstract

We consider the challenging problem of using domain knowledge to improve deep reinforcement learning policies. To this end, we propose LEGIBLE, a novel approach, following a multi-step process, which starts by mining rules from a deep RL policy, constituting a partially symbolic representation. These rules describe which decisions the RL policy makes and which it avoids making. In the second step, we generalize the mined rules using domain knowledge expressed as metamorphic relations. We adapt these relations from software testing to RL to specify expected changes of actions in response to changes in observations. The third step is evaluating generalized rules to determine which generalizations improve performance when enforced. These improvements show weaknesses in the policy, where it has not learned the general rules and thus can be improved by rule guidance. LEGIBLE supported by metamorphic relations provides a principled way of expressing and enforcing domain knowledge about RL environments. We show the efficacy of our approach by demonstrating that it effectively finds weaknesses, accompanied by explanations of these weaknesses, in eleven RL environments and by showcasing that guiding policy execution with rules improves performance w.r.t. gained reward.
