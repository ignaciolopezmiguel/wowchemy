---
title: "OFTEN-DeepRL: On-the-Fly Teaching of Ethical Norms to Deep Reinforcement
  Learning Agents"
publication_types:
  - "1"
authors:
  - admin
  - Sebastian Adam
  - Ezio Bartocci
  - Thomas Eiter
  - Martin Tappler
publication: In the 28th European Conference on Artificial Intelligence
publication_short: In *ECAI'25*
abstract: >-
  AI agents trained with reinforcement learning (RL) usually focus on completing
  their intended tasks without detours, as doing so typically maximizes their
  reward. However, real-world deployment requires agents that not only achieve
  their goals but also comply with ethical and societal norms that may conflict
  with their learned behavior.

  In this work, we present OFTEN-DeepRL, an approach to integrate ethical norms into agents trained with deep reinforcement learning. The approach starts by training an RL policy focused on task performance. Building upon such a pre-trained policy, OFTEN-DeepRL adapts the policy through norm-guided training. For a combination of observations and domain knowledge, we employ a logic program that generates norm-compliant plans for the agent using answer set programming (ASP) within a given planning horizon. These plans serve as demonstrations for fine-tuning the agent's policy in the norm-guided training phase, guiding it toward behavior that remains effective while respecting the specified norms.

  We validate our approach with three types of scenarios: Pac-Man, a gardener simulation, and a SUMO-RL traffic control scenario. In all settings, agents fine-tuned with OFTEN-DeepRL achieve comparable task performance while significantly reducing norm violations.
draft: false
featured: false
image:
  filename: image_ecai25.png
  focal_point: Smart
  preview_only: false
date: 2025-10-17T08:24:40.295Z
---
