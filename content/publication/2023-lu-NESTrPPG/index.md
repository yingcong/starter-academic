---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Neuron Structure Modeling for Generalizable Remote Physiological Measurement"
subtitle: ''
summary: ''
authors:
- Hao Lu
- Zitong Yu
- Xuesong Niu
- admin
# author_notes:
# - ""
# - ""
# - ""
# - "Corresponding Author"
tags: ['AI for Healthcare', 'Domain Generalization']
categories: []
date: '2023-06-13'
# lastmod: 2023-6-07T11:07:49+08:00
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
publishDate: '2023-6-07T03:07:48.919569Z'
publication_types:
- '1'
abstract: 'Remote photoplethysmography (rPPG) technology has drawn increasing attention in recent years. It can extract Blood Volume Pulse (BVP) from facial videos, making many applications like health monitoring and emotional analysis more accessible. However, as the BVP signal is easily affected by environmental changes, existing methods struggle to generalize well for unseen domains. In this paper, we systematically address the domain shift problem in the rPPG measurement task. We show that most domain generalization methods do not work well in this problem, as domain labels are ambiguous in complicated environmental changes. In light of this, we propose a domain-label-free approach called NEuron STructure modeling (NEST). NEST improves the generalization capacity by maximizing the coverage of feature space during training, which reduces the chance for under-optimized feature activation during inference. Besides, NEST can also enrich and enhance domain invariant features across multi-domain. We create and benchmark a large-scale domain generalization protocol for the rPPG measurement task. Extensive experiments show that our approach outperforms the state-of-the-art methods on both cross-dataset and intra-dataset settings.'
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*'
url_code: 'https://github.com/LuPaoPao/NEST-rPPG'
# url_pdf: 'publication/lu-2023-NESTrPPG/lu-2023-NESTrPPG.pdf'
# url_video: 'publication/lu-2023-NESTrPPG/video.mp4'
# url_project: 

---
