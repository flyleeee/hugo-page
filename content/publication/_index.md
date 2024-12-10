---
publication_types:
  - "3"
authors:
  - Haizhou Shi
  - admin
  - Ligong Han
  - Dimitris Metaxas
  - Huan Zhang
  - Hao Wang
author_notes:
  - Equal contribution
  - Equal contribution
publication: "Arxiv"
publication_short: "Arxiv"
abstract: Estimating the uncertainty of responses of Large Language Models~(LLMs) remains a critical challenge. While recent Bayesian methods have demonstrated effectiveness in quantifying uncertainty through low-rank weight updates, they typically require complex fine-tuning or post-training procedures. In this paper, we propose Training-Free Bayesianization~(TFB), a novel framework that transforms existing off-the-shelf trained LoRA adapters into Bayesian ones without additional training. TFB systematically searches for the maximally acceptable level of variance in the weight posterior, constrained within a family of low-rank isotropic Gaussian distributions. We theoretically demonstrate that under mild conditions, this search process is equivalent to variational inference for the weights. Through comprehensive experiments, we show that TFB achieves superior uncertainty estimation and generalization compared to existing methods while eliminating the need for complex training procedures. Code will be available at [this https URL](https://github.com/Wang-ML-Lab/bayesian-peft).

url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: "Training-Free Bayesianization for Low-Rank Adapters of Large Language Models"
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
date: 2024-12-10T00:00:00Z
url_pdf: "https://arxiv.org/pdf/2412.05723"
url_slides: ""
publishDate: 2024-12-10T00:00:00Z
url_poster: "https://nips.cc/media/PosterPDFs/NeurIPS%202024/95507.png?t=1731732028.1365483"
url_code: "https://github.com/Wang-ML-Lab/bayesian-peft"
links:
- name: arxiv
  url: https://arxiv.org/abs/2412.05723
---
