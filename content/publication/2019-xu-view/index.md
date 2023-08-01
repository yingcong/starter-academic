---
# Documentation: https://wowchemy.com/docs/managing-content/

title: View Independent Generative Adversarial Network for Novel View Synthesis
subtitle: ''
summary: ''
authors:
- Xiaogang Xu
- admin
- Jiaya Jia
tags: ['Generative Adversarial Networks', 'Novel View Synthesis', 'Face Manipulation']
categories: []
date: '2019-01-01'
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
publishDate: '2021-06-12T03:07:48.090838Z'
publication_types:
- '1'
abstract: 'Synthesizing novel views from a 2D image requires to infer 3D structure and project it back to 2D from a new viewpoint. In this paper, we propose an encoder-decoder based generative adversarial network VI-GAN to tackle this problem. Our method is to let the network, after seeing many images of objects belonging to the same category in different views, obtain essential knowledge of intrinsic properties of the objects. To this end, an encoder is designed to extract view-independent feature that characterizes intrinsic properties of the input image, which includes 3D structure, color, texture etc. We also make the decoder hallucinate the image of a novel view based on the extracted feature and an arbitrary user-specific camera pose. Extensive experiments demonstrate that our model can synthesize high-quality images in different views with continuous camera poses, and is general for various applications.'
publication: '*Proceedings of the IEEE International Conference on Computer Vision* (**Oral**, Acceptance Rate: 2.1%)'
url_pdf: 'https://openaccess.thecvf.com/content_ICCV_2019/html/**Xu_View_Independent_Generative_Adversarial_Network_for_Novel_View_Synthesis_ICCV_2019_paper.html'

---
