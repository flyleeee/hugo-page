---
abstract: Natural Language Processing (NLP) models have gained great success on
  clean texts, but they are known to be vulnerable to adversarial examples
  typically crafted by synonym substitutions. In this paper, we target to solve
  this problem and find that word embedding is important to the certified
  robustness of NLP models. Given the findings, we propose the Embedding
  Interval Bound Constraint (EIBC) triplet loss to train robustness-aware word
  embeddings for better certified robustness. We optimize the EIBC triplet loss
  to reduce distances between synonyms in the embedding space, which is
  theoretically proven to make the verification boundary tighter. Meanwhile, we
  enlarge distances among non-synonyms, maintaining the semantic representation
  of word embeddings.Our method is conceptually simple and componentized. It can
  be easily combined with IBP training and improves the certified robust
  accuracy from 76.73\% to 84.78\% on the IMDB dataset while reducing the
  training epochs to half. Experiments demonstrate that our method outperforms
  various state-of-the-art certified defense baselines and generalizes well to
  unseen substitutions.
slides: ""
url_pdf: https://aclanthology.org/2023.findings-acl.42.pdf
publication_types:
  - "1"
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
authors:
  - admin
  - Yichen Yang
  - Di He
  - Kun He
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *Findings of ACL 2023*
abstract: Natural Language Processing (NLP) models have gained great success on clean texts, but they are known to be vulnerable to adversarial examples typically crafted by synonym substitutions. In this paper, we target to solve this problem and find that word embedding is important to the certified robustness of NLP models. Given the findings, we propose the Embedding Interval Bound Constraint (EIBC) triplet loss to train robustness-aware word embeddings for better certified robustness.
url_dataset: ""
url_project: ""
publication_short: In *Findings of ACL 2023*
url_source: ""
url_video: ""
title: Robustness-Aware Word Embedding Improves Certified Robustness to Adversarial Word Substitutions
doi: ""
featured: true
tags:
  - Certified Robustness
  - Trustworthy AI
  - Natural Language Processing
projects: []
image:
  filename: avatar.jpg
  focal_point: Center
  preview_only: false
date: 2023-06-01T00:00:00Z
url_slides: ""
publishDate: 2023-05-06T00:00:00Z
url_poster: ""
url_code: https://github.com/JHL-HUST/EIBC-IBP
links:
- name: ACL Anthology
  url: https://aclanthology.org/2023.findings-acl.42/
---
