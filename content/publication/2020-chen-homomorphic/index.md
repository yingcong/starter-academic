---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Homomorphic Interpolation Network for Unpaired Image-to-image Translation
subtitle: ''
summary: ''
authors:
- admin
- Jiaya Jia
tags: ['Latent Space Interpolation', 'Generative Adversarial Networks', 'Face Manipulation', 'Image-to-image Translation']
categories: []
date: '2020-01-01'
lastmod: 2021-06-12T11:07:49+08:00
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
publishDate: '2021-06-12T03:07:48.919569Z'
publication_types:
- '2'
abstract: 'Generative adversarial networks have achieved great success in unpaired image-to-image translation. Cycle consistency, a key component for this task, allows modeling the relationship between two distinct domains without paired data. In this paper, we propose an alternative framework, as an extension of latent space interpolation, to consider the intermediate region between two domains during translation. It is based on the fact that in a flat and smooth latent space, there exist many paths that connect two sample points. Properly selecting paths makes it possible to change only certain image attributes, which is useful for generating intermediate images between the two domains. With this idea, our framework includes an encoder, an interpolator and a decoder. The encoder maps natural images to a convex and smooth latent space where interpolation is applicable. The interpolator controls the interpolation path so that desired intermediate samples can be obtained. Finally, the decoder inverts interpolated features back to pixel space. We also show that by choosing different reference images and interpolation paths, this framework can be applied to multi-domain and multi-modal translation. Extensive experiments manifest that our framework achieves superior results and is flexible for various tasks.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence*'
url_code: 'https://github.com/yingcong/HomoInterpGAN'
url_video: 'publication/2020-chen-homomorphic/video.mp4'
---
