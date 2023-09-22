---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Label Name is Mantra: Unifying Point Cloud Segmentation across Heterogeneous Datasets"
subtitle: ''
summary: ''
authors:
- Yixun Liang
- Hao He
- Shishi Xiao
- Hao Lu
- admin
tags: ['3D Vision']
categories: []
date: '2023-03-19'
lastmod: 2023-03-19T11:07:49+08:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Smart'
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-03-19T03:07:48.919569Z'
publication_types:
- '2'
abstract: 'Point cloud segmentation is a fundamental task in 3D vision that serves a wide range of applications. Although great progresses have been made these years, its practical usability is still limited by the availability of training data. Existing approaches cannot make full use of multiple datasets on hand due to the label mismatch among different datasets. In this paper, we propose a principled approach that supports learning from heterogeneous datasets with different label sets. Our idea is to utilize a pre-trained language model to embed discrete labels to a continuous latent space with the help of their label names. This unifies all labels of different datasets, so that joint training is doable. Meanwhile, classifying points in the continuous 3D space by their vocabulary tokens significantly increase the generalization ability of the model in comparison with existing approaches that have fixed decoder architecture. Besides, we also integrate prompt learning in our framework to alleviate data shifts among different data sources. Extensive experiments demonstrate that our model outperforms the state-of-the-art by a large margin.'
publication: '*arXiv Preprint*'
url_code: 'https://github.com/YixunLiang/MantraNet'
# url_pdf: 'publication/liang-2023-label/liang-2023-label.pdf'
# url_project: 

---
