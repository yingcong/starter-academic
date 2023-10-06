---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Ref-NeuS: Ambiguity-Reduced Neural Implicit Surface Learning for Multi-View Reconstruction with Reflection"
subtitle: ''
summary: ''
authors:
- Wenhang Ge
- Tao Hu
- Haoyu Zhao
- Shu Liu
- admin
tags: ['3D Vision']
categories: []
date: '2023-10-01'
lastmod: 2023-06-20T03:08:22+08:00
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
publishDate: '2023-06-20T03:08:22.919569Z'
publication_types:
- '2'
abstract: 'Neural implicit surface learning has shown significant progress in multi-view 3D reconstruction, where an object is represented by multilayer perceptrons that provide continuous implicit surface representation and view-dependent radiance. However, current methods often fail to accurately reconstruct reflective surfaces, leading to severe ambiguity. To overcome this issue, we propose Ref-NeuS, which aims to reduce ambiguity by attenuating the effect of reflective surfaces. Specifically, we utilize an anomaly detector to estimate an explicit reflection score with the guidance of multi-view context to localize reflective surfaces. Afterward, we design a reflection-aware photometric loss that adaptively reduces ambiguity by modeling rendered color as a Gaussian distribution, with the reflection score representing the variance. We show that together with a reflection direction-dependent radiance, our model achieves high-quality surface reconstruction on reflective surfaces and outperforms the state-of-the-arts by a large margin. Besides, our model is also comparable on general surfaces.'
url_code: 'https://github.com/g3956/Ref-NeuS'
publication: 'In *Proceedings of the IEEE International Conference on Computer Vision (ICCV)* (**Oral**, **Best Paper Final List**, top 0.2\%)'
#url_video: 'publication/chen-2020-homomorphic/video.mp4'
url_project: 'https://g3956.github.io/'

---
