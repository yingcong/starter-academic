---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Delving into Deep Imbalanced Regression
subtitle: ''
summary: ''
authors:
- Yuzhe Yang
- Kaiwen Zha
- admin
- Hao Wang
- Dina Katabi
tags: ['Machine Learning']
categories: []
date: '2021-06-01'
# lastmod: 2021-06-12T11:07:49+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-06-12T03:07:49.197787Z'
publication_types: ["1"]
abstract: 'Real-world data often exhibit imbalanced distributions, where certain target values have significantly fewer observations. Existing techniques for dealing with imbalanced data focus on targets with categorical indices, i.e., different classes. However, many tasks involve continuous targets, where hard boundaries between classes do not exist. We define Deep Imbalanced Regression (DIR) as learning from such imbalanced data with continuous targets, dealing with potential missing data for certain target values, and generalizing to the entire target range. Motivated by the intrinsic difference between categorical and continuous label space, we propose distribution smoothing for both labels and features, which explicitly acknowledges the effects of nearby targets, and calibrates both label and learned feature distributions. We curate and benchmark large-scale DIR datasets from common real-world tasks in computer vision, natural language processing, and healthcare domains. Extensive experiments verify the superior performance of our strategies. Our work fills the gap in benchmarks and techniques for practical imbalanced regression problems.'
publication: 'In *International Conference on Machine Learning* (**Long Talk**, Acceptance Rate: 3\%)'
# publication_short: In *ICML*
url_pdf: 'https://arxiv.org/abs/2102.09554'
url_code: 'https://github.com/YyzHarry/imbalanced-regression'
url_project: 'http://dir.csail.mit.edu'
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links: 
- name: post
  url: "https://towardsdatascience.com/strategies-and-tactics-for-regression-on-imbalanced-data-61eeb0921fca"
---