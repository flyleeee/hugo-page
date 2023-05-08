---
title: 'Robustness-Aware Word Embedding Improves Certified Robustness to Adversarial Word Substitutions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yichen Yang
  - Di He
  - Kun He

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ACL 2023 Findings*
publication_short: In *Findings of ACL 2023* 

abstract: Natural Language Processing (NLP) models have gained great success on clean texts, but they are known to be vulnerable to adversarial examples typically crafted by synonym substitutions. In this paper, we target to solve this problem and find that word embedding is important to the certified robustness of NLP models. Given the findings, we propose the Embedding Interval Bound Constraint (EIBC) triplet loss to train robustness-aware word embeddings for better certified robustness. We optimize the EIBC triplet loss to reduce distances between synonyms in the embedding space, which is theoretically proven to make the verification boundary tighter. Meanwhile, we enlarge distances among non-synonyms, maintaining the semantic representation of word embeddings.Our method is conceptually simple and componentized. It can be easily combined with IBP training and improves the certified robust accuracy from 76.73\% to 84.78\% on the IMDB dataset while reducing the training epochs to half. Experiments demonstrate that our method outperforms various state-of-the-art certified defense baselines and generalizes well to unseen substitutions.
# Summary. An optional shortened abstract.
summary: Natural Language Processing (NLP) models have gained great success on clean texts, but they are known to be vulnerable to adversarial examples typically crafted by synonym substitutions. In this paper, we target to solve this problem and find that word embedding is important to the certified robustness of NLP models. Given the findings, we propose the Embedding Interval Bound Constraint (EIBC) triplet loss to train robustness-aware word embeddings for better certified robustness. 

tags: 
- Adversaral Robustness
- Certified Robustness
- Natural Language Processing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  filename: avatar.jpg
  focal_point: Smart
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example
  []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---



