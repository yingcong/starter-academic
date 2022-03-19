---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SC-GAN: Image Synthesis via Semantic Composition'
subtitle: ''
summary: ''
authors:
- Yi Wang
- Lu Qi
- admin
- Xiangyu Zhang
- Jiaya Jia
tags: ['Generative Adversarial Networks', Face Manipulation]
categories: []
date: '2021-07-01'
# lastmod: 2021-06-12T11:07:49+08:00
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
# publishDate: ''
publication_types: ["1"]
abstract: 'In this paper, we present a novel approach to synthesize realistic images based on their semantic layouts. The core idea is that for objects with similar appearance, they also share similar representation. To this end, we first regress semantic layouts to natural images, with intermediate representation that contains both semantic and appearance information. Then we propose a dynamic weighted network that takes these intermediate representations as a condition to generate high-quality results. We demonstrate that our method gives the compelling generation performance qualitatively and quantitatively with extensive experiments on benchmarks.'
publication: 'In *Proceedings of the IEEE International Conference on Computer Vision*'
# publication_short: In *ICML*
# url_pdf: 'https://arxiv.org/abs/2102.09554'
# url_code: 'https://github.com/YyzHarry/imbalanced-regression'
# url_project: 'http://dir.csail.mit.edu'
# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Image_Synthesis_via_Semantic_Composition_ICCV_2021_paper.pdf'
url_code: 'https://github.com/dvlab-research/SCGAN'
---