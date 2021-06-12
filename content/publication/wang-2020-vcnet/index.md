---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'VCNet: A Robust Approach to Blind Image Inpainting'
subtitle: ''
summary: ''
authors:
- Yi Wang
- admin
- Xin Tao
- Jiaya Jia
tags: ['Generative Adversarial Networks', 'Image Inpainting']
categories: []
date: '2020-01-01'
lastmod: 2021-06-12T11:07:48+08:00
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
publishDate: '2021-06-12T03:07:48.772798Z'
publication_types:
- '1'
abstract: 'Blind inpainting is a task to automatically complete visual contents without specifying masks for missing areas in an image. Previous works assume missing region patterns are known, limiting its application scope. In this paper, we relax the assumption by defining a new blind inpainting setting, making training a blind inpainting neural system robust against various unknown missing region patterns. Specifically, we propose a two-stage visual consistency network (VCN), meant to estimate where to fill (via masks) and generate what to fill. In this procedure, the unavoidable potential mask prediction errors lead to severe artifacts in the subsequent repairing. To address it, our VCN predicts semantically inconsistent regions first, making mask prediction more tractable. Then it repairs these estimated missing regions using a new spatial normalization, enabling VCN to be robust to the mask prediction errors. In this way, semantically convincing and visually compelling content is thus generated. Extensive experiments are conducted, showing our method is effective and robust in blind image inpainting. And our VCN allows for a wide spectrum of applications.'
publication: 'In *European Conference on Computer Vision*'
url_pdf: 'https://arxiv.org/abs/2003.06816'
url_code: 'https://github.com/shepnerd/blindinpainting_vcnet'
---
