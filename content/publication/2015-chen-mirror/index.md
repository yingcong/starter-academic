---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Mirror representation for modeling view-specific transform in person re-identification
subtitle: ''
summary: ''
authors:
- admin
- Wei-Shi Zheng
- Jianhuang Lai
tags: ['Person Re-identification', 'Metric Learning']
categories: []
date: '2015-01-01'
lastmod: 2021-06-12T11:07:46+08:00
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
publishDate: '2021-06-12T03:07:46.082073Z'
publication_types:
- '1'
abstract: 'Person re-identification concerns the matching of pedestrians across disjoint camera views. Due to the changes of viewpoints, lighting conditions and camera features, images of the same person from different views always appear differently, and thus feature representations across disjoint camera views of the same person follow different distributions. In this work, we propose an effective, low cost and easy-to-apply schema called the Mirror Representation, which embeds the view-specific feature transformation and enables alignment of the feature distributions across disjoint views for the same person. The proposed Mirror Representation is also designed to explicitly model the relation between different view-specific transformations and meanwhile control their discrepancy. With our Mirror Representation, we can enhance existing subspace/ metric learning models significantly, and we particularly show that kernel marginal fisher analysis significantly outperforms the current state-of-the-art methods through extensive experiments on VIPeR, PRID450S and CUHK01.'
publication: 'Proceedings of the *International Conference on Artificial Intelligence*'
url_pdf: 'https://www.ijcai.org/Proceedings/15/Papers/479.pdf'
url_code: 'publication/2015-chen-mirror/demo_Mirror.zip'
links: 
- name: Feature
  url: "publication/2015-chen-mirror/demo_feat.zip"
---
