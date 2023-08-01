---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Real-time 6K Image Rescaling with Rate-distortion Optimization"
subtitle: ''
summary: ''
authors:
- Chenyang Qi
- Xin Yang
- Ka Leong Chang
- admin
- Qifeng Chen
tags: ['Image Rescalling', 'Image Compression']
categories: []
date: '2023-04-03'
lastmod: Mon, 3 Apr 2023 15:21:56 UTC
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
publishDate: 2023-05-03T22:40:48+08:00
publication_types:
- '2'
abstract: 'Contemporary image rescaling aims at embedding a high-resolution (HR) image into a low-resolution (LR) thumbnail image that contains embedded information for HR image reconstruction. Unlike traditional image super-resolution, this enables high-fidelity HR image restoration faithful to the original one, given the embedded information in the LR thumbnail. However, state-of-the-art image rescaling methods do not optimize the LR image file size for efficient sharing and fall short of real-time performance for ultra-high-resolution (e.g., 6K) image reconstruction. To address these two challenges, we propose a novel framework (HyperThumbnail) for real-time 6K rate-distortion-aware image rescaling. Our framework first embeds an HR image into a JPEG LR thumbnail by an encoder with our proposed quantization prediction module, which minimizes the file size of the embedding LR JPEG thumbnail while maximizing HR reconstruction quality. Then, an efficient frequency-aware decoder reconstructs a high-fidelity HR image from the LR one in real time. Extensive experiments demonstrate that our framework outperforms previous image rescaling baselines in rate-distortion performance and can perform 6K image reconstruction in real time.'
publication: '*IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR)*'
url_code: 'https://github.com/AbnerVictor/HyperThumbnail'
# url_video: ''
# url_project: 

---
