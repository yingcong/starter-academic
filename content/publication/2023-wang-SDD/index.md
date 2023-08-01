---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Not All Steps are Created Equal: Selective Diffusion Distillation for Image Manipulation"
subtitle: ''
summary: ''
authors:
- Luozhou Wang
- Shuai Yang
- Shu Liu
- admin
tags: ['Diffusion']
categories: []
date: '2023-06-20'
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
abstract: 'Conditional diffusion models have demonstrated impressive performance in image manipulation tasks. The general pipeline involves adding noise to the image and then denoising it. However, this method faces a trade-off problem: adding too much noise affects the fidelity of the image while adding too little affects its editability. This largely limits their practical applicability. In this paper, we propose a novel framework, Selective Diffusion Distillation (SDD), that ensures both the fidelity and editability of images. Instead of directly editing images with a diffusion model, we train a feedforward image manipulation network under the guidance of the diffusion model. Besides, we propose an effective indicator to select the semantic-related timestep to obtain the correct semantic guidance from the diffusion model. This approach successfully avoids the dilemma caused by the diffusion process. Our extensive experiments demonstrate the advantages of our framework.'
url_code: 'https://github.com/AndysonYs/Selective-Diffusion-Distillation'
publication: 'In *Proceedings of the IEEE International Conference on Computer Vision (ICCV)*'
#url_video: 'publication/chen-2020-homomorphic/video.mp4'
url_pdf: https://arxiv.org/abs/2307.08448


---
