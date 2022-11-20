---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "RC-MVSNet: Unsupervised Multi-View Stereo with Neural Rendering"
subtitle: ''
summary: ''
authors:
- Di Chang
-  Aljaz Bozic
-  Tong Zhang
-  Qingsong Yan
-  admin
-  Sabine Susstrunk
-  Matthias Niebner
tags: ['NeRF', '3D Vision']
categories: []
date: '2022-10-23'
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
publication_types: ["1"]
abstract: 'Finding accurate correspondences among different views is the Achilles heel of unsupervised Multi-View Stereo (MVS). Existing methods are built upon the assumption that corresponding pixels share similar photometric features. However, multi-view images in real scenarios observe non-Lambertian surfaces and experience occlusions. In this work, we propose a novel approach with neural rendering (RC-MVSNet) to solve such ambiguity issues of correspondences among views. Specifically, we impose a depth rendering consistency loss to constrain the geometry features close to the object surface to alleviate occlusions. Concurrently, we introduce a reference view synthesis loss to generate consistent supervision, even for non-Lambertian surfaces. Extensive experiments on DTU and Tanks\&Temples benchmarks demonstrate that our RC-MVSNet approach achieves state-of-the-art performance over unsupervised MVS frameworks and competitive performance to many supervised methods.'
publication: '*Proceedings of the European conference on computer vision (ECCV)*'
url_pdf: 'https://arxiv.org/abs/2203.03949'
url_project: '[publication/chen-2020-domain/DAI2I.mp4](https://boese0601.github.io/rc-mvsnet/)'
url_code: 'https://github.com/Boese0601/RC-MVSNet'
---
