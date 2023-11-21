---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Rethinking Rendering in Generalizable Neural Surface Reconstruction: A Learning-based Solution"
subtitle: ''
summary: ''
authors:
- Yixun Liang
- Hao He
- admin
tags: ['3D Vision']
categories: []
date: '2023-11-10'
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
publishDate: '2023-05-30T03:07:48.919569Z'
publication_types:
- '1'
abstract: 'Generalizable neural surface reconstruction techniques have attracted great attention in recent years. However, they encounter limitations of low confidence depth distribution and inaccurate surface reasoning due to the oversimplified volume rendering process employed. In this paper, we present Reconstruction TRansformer (ReTR), a novel framework that leverages the transformer architecture to redesign the rendering process, enabling complex photon-particle interaction modeling. It introduces a learnable meta-ray token and utilizes the cross-attention mechanism to simulate the interaction of photons with sampled points and render the observed color. Meanwhile, by operating within a high-dimensional feature space rather than the color space, ReTR mitigates sensitivity to projected colors in source views. Such improvements result in accurate surface assessment with high confidence. We demonstrate the effectiveness of our approach on various datasets, showcasing how our method outperforms the current state-of-the-art approaches in terms of reconstruction quality and generalization ability.'
publication: '*Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS)*'
url_code: 'https://github.com/YixunLiang/ReTR'
# url_pdf: 'publication/liang-2023-retr/liang-2023-retr.pdf'
# url_video: 'publication/liang-2023-retr/video.mp4'
url_project: 'https://yixunliang.github.io/ReTR'

---
