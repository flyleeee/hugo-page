---
publication_types:
  - "1"
authors:
  - admin
  - Haizhou Shi
  - Ligong Han
  - Dimitris Metaxas
  - Hao Wang
author_notes:
  - Equal contribution
  - Equal contribution
publication: "Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024."
publication_short: "NeurIPS 2024"
abstract: Large Language Models (LLMs) often suffer from overconfidence during inference, particularly when adapted to downstream domain-specific tasks with limited data. Previous work addresses this issue by employing approximate Bayesian estimation after the LLMs are trained, enabling them to quantify uncertainty. However, such post-training approaches' performance is severely limited by the parameters learned during training. In this paper, we go beyond post-training Bayesianization and propose Bayesian Low-Rank Adaptation by Backpropagation (BLoB), an algorithm that continuously and jointly adjusts both the mean and covariance of LLM parameters throughout the whole fine-tuning process. Our empirical results verify the effectiveness of BLoB in terms of generalization and uncertainty estimation, when evaluated on both in-distribution and out-of-distribution data.

url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: "BLoB: Bayesian Low-Rank Adaptation by Backpropagation for Large Language Models"
doi: ""
featured: true
tags:
  - Bayesain Deep Learning
  - Trustworthy AI
  - Large Language Models
projects: []
image:
  filename: avatar.png
  focal_point: Center
  preview_only: false
date: 2024-06-17T00:00:00Z
url_pdf: "https://arxiv.org/pdf/2406.11675"
url_slides: "https://nips.cc/media/neurips-2024/Slides/95507.pdf"
publishDate: 2024-06-17T00:00:00Z
url_poster: "https://nips.cc/media/PosterPDFs/NeurIPS%202024/95507.png?t=1731732028.1365483"
url_code: "https://github.com/Wang-ML-Lab/bayesian-peft"
links:
- name: arxiv
  url: https://arxiv.org/abs/2406.11675
- name: NeurIPS
  url: https://nips.cc/virtual/2024/poster/95507
---
