---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Representation Compensation Networks for Continual Semantic Segmentation
subtitle: ''
summary: ''
authors:
- Chang-Bin Zhang
- Jia-Wen Xiao
- Xialei Liu
- admin
- Ming-Ming Cheng
tags: ['Machine Learning']
categories: []
date: '2022-06-01'
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
publishDate: ''
publication_types: ["1"]
abstract: 'In this work, we study the continual semantic segmentation problem, where the deep neural networks are required to incorporate new classes continually without catastrophic forgetting. We propose to use a structural re-parameterization mechanism, named representation compensation (RC) module, to decouple the representation learning of both old and new knowledge. The RC module consists of two dynamically evolved branches with one frozen and one trainable. Besides, we design a pooled cube knowledge distillation strategy on both spatial and channel dimensions to further enhance the plasticity and stability of the model. We conduct experiments on two challenging continual semantic segmentation scenarios, continual class segmentation and continual domain segmentation. Without any extra computational overhead and parameters during inference, our method outperforms state-of-the-art performance.'
# publication_short: In *ICML*
publication: 'In *Computer Vision and Pattern Recognition*'
url_pdf: 'publication/zhang-2022-representation'
url_code: 'https://github.com/zhangchbin/RCIL'
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
---