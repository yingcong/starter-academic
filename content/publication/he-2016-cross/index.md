---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Cross-view Transformation based Sparse Reconstruction for Person Re-identification
subtitle: ''
summary: ''
authors:
- Wei-Xiong He
- admin
- Jian-Huang Lai
tags: ['Person Re-identification']
categories: []
date: '2016-01-01'
lastmod: 2021-06-12T11:07:47+08:00
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
publishDate: '2021-06-12T03:07:46.991726Z'
publication_types:
- '1'
abstract: 'Based on minimum reconstruction error criterion and the intrinsic sparse property of natural data, sparse representation (SR) has shown promising performance on various image recognition tasks. However, in the field of person re-identification (re-id), the state-of-the-art is still dominated by other methods such as metric learning or CNN. It is because samples in one view may not be representative enough to represent samples from another view. As such, the reconstruction error could be excessive, and different pedestrians are indistinguishable with the coefficient produced by sparse representation. In this paper, we proposed an asymmetric sparse representation to address this problem. Samples of different camera views (gallery and probe samples) are mapped to a common latent space and the sparse coefficient is generated in this space. In this way, the representation power is enhanced and the sparse coefficient becomes more reliable. The similarities of different samples are determined by the enhanced sparse coefficient, which allows more discriminative matching across different camera views. Extensive experiments on CAVIAR4REID, iLIDS-VID and PRID 2011 datasets have demonstrated the merits of our approach.'
publication: '*International Conference on Pattern Recognition*'
url_pdf: 'https://ieeexplore.ieee.org/document/7900161'
---
