---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching"
subtitle: ''
summary: ''
authors:
- Yixun Liang
- Xin Yang
- Jiantao Lin
- Haodong Li
- Xiaogang Xu
- admin
tags: ['3D Vision', 'Diffusion Model']
categories: []
date: '2023-11-21'
# lastmod: 2023-05-30T11:07:49+08:00
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
publishDate: '2023-11-21T03:07:48.919569Z'
publication_types:
- '1'
abstract: 'The recent advancements in text-to-3D generation mark a significant milestone in generative models, unlocking new possibilities for creating imaginative 3D assets across various real-world scenarios. While recent advancements in text-to-3D generation have shown promise, they often fall short in rendering detailed and high-quality 3D models. This problem is especially prevalent as many methods base themselves on Score Distillation Sampling (SDS). This paper identifies a notable deficiency in SDS, that it brings inconsistent and low-quality updating direction for the 3D model, causing the over-smoothing effect. To address this, we propose a novel approach called Interval Score Matching (ISM). ISM employs deterministic diffusing trajectories and utilizes interval-based score matching to counteract over-smoothing. Furthermore, we incorporate 3D Gaussian Splatting into our text-to-3D generation pipeline. Extensive experiments show that our model largely outperforms the state-of-the-art in quality and training efficiency.'
publication: '*Arxiv*'
url_code: 'https://github.com/EnVision-Research/LucidDreamer'
url_pdf: 'https://arxiv.org/abs/2311.11284'
# url_video: 'publication/liang-2023-retr/video.mp4'
# url_project: 'https://yixunliang.github.io/ReTR'

---
