---
title: "Contextualized Topic Modeling with Python (EACL2021)"
subtitle: "Combining BERT and friends with Neural Variational Topic Models"

# Summary for listings and search engines
summary: "In this blog post, I discuss our latest published paper on topic modeling in which we introduce Contextualized Topic Models."

# Link this post with a project
projects: [CTM]

# Date published
date: "2021-08-11T00:00:00Z"

# Date updated
lastmod: "2021-08-11T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'CTM Architecture'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- Federico Bianchi


tags:
- Academic
- AI

categories:
- Topic Models
- NLP
- Language Models

links:
 - name: Read on Medium
   url: https://towardsdatascience.com/contextualized-topic-modeling-with-python-eacl2021-eacf6dfa576

url_pdf: 'https://www.aclweb.org/anthology/2021.eacl-main.143.pdf'
url_code: 'https://github.com/MilaNLProc/contextualized-topic-models'

---

## Overview

Suppose we have a small set of documents in Portuguese that is not large enough to reliably run standard topic modeling algorithms. However, we have enough English documents in the same domain. With our cross-lingual zero-shot topic model (ZeroShotTM), we can first learn topics on English and then predict topics for Portuguese documents (as long as we use pre-trained representations that account for both English and Portuguese).

[Read More](https://towardsdatascience.com/contextualized-topic-modeling-with-python-eacl2021-eacf6dfa576)
