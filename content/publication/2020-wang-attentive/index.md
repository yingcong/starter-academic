---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Attentive normalization for conditional image generation
subtitle: ''
summary: ''
authors:
- Yi Wang
- admin
- Xiangyu Zhang
- Jian Sun
- Jiaya Jia
tags: ['Generative Adversarial Networks', 'Image Generation']
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
publishDate: '2021-06-12T03:07:48.613815Z'
publication_types:
- '1'
abstract: 'Traditional convolution-based generative adversarial networks synthesize images based on hierarchical local operations, where long-range dependency relation is implicitly modeled with a Markov chain. It is still not sufficient for categories with complicated structures. In this paper, we characterize long-range dependence with attentive normalization (AN), which is an extension to traditional instance normalization. Specifically, the input feature map is softly divided into several regions based on its internal semantic similarity, which are respectively normalized. It enhances consistency between distant regions with semantic correspondence. Compared with self-attention GAN, our attentive normalization does not need to measure the correlation of all locations, and thus can be directly applied to large-size feature maps without much computational burden. Extensive experiments on class-conditional image generation and semantic inpainting verify the efficacy of our proposed module.'
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition* (**Oral**, Acceptance Rate: 5.7%)'
url_pdf: 'https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Attentive_Normalization_for_Conditional_Image_Generation_CVPR_2020_paper.html'
url_code: 'https://github.com/Jia-Research-Lab/AttenNorm'
---
