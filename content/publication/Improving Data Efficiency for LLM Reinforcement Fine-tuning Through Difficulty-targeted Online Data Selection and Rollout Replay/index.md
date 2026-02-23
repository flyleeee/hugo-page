---
publication_types:
  - "3"
authors:
  - Yifan Sun
  - Jingyan Shen
  - admin
  - Tianyu Chen
  - Zhendong Wang
  - Mingyuan Zhou
  - Huan Zhang
author_notes:
  - Equal contribution
  - Equal contribution
  - Equal contribution
publication: "Advances in Neural Information Processing Systems (NeurIPS), 2025"
publication_short: "NeurIPS 2025"
abstract: >
  Reinforcement learning (RL) has become an effective approach for fine-tuning large language models (LLMs), particularly to enhance their reasoning capabilities. However, RL fine-tuning remains highly resource-intensive, and existing work has largely overlooked the problem of data efficiency. In this paper, we propose two techniques to improve data efficiency in LLM RL fine-tuning: difficulty-targeted online data selection and rollout replay. We introduce the notion of adaptive difficulty to guide online data selection, prioritizing questions of moderate difficulty that are more likely to yield informative learning signals. To estimate adaptive difficulty efficiently, we develop an attention-based framework that requires rollouts for only a small reference set of questions. The adaptive difficulty of the remaining questions is then estimated based on their similarity to this set. To further reduce rollout cost, we introduce a rollout replay mechanism inspired by experience replay in traditional RL. This technique reuses recent rollouts, lowering per-step computation while maintaining stable updates. Experiments across 6 LLM-dataset combinations show that our method reduces RL fine-tuning time by 23% to 62% while reaching the same level of performance as the original GRPO algorithm. Our code is available at [this https URL](https://github.com/ASTRAL-Group/data-efficient-llm-rl).
image:
  filename: featured.png
  focal_point: Center
  preview_only: false
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: "Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay"
doi: ""
featured: false
tags:
  - RL Fine-tuing
  - Data Selection
  - Large Language Models
projects: []
date: 2025-06-10T00:00:00Z
url_pdf: "https://arxiv.org/pdf/2506.05316"
url_slides: ""
publishDate: 2025-06-10T00:00:00Z
url_poster: 
url_code: 
links:
- name: arxiv
  url: https://arxiv.org/abs/2506.05316
---
