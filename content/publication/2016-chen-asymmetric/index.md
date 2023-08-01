---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An asymmetric distance model for cross-view feature mapping in person reidentification
subtitle: ''
summary: ''
authors:
- admin
- Wei-Shi Zheng
- Jian-Huang Lai
- Pong C Yuen
tags: ['Person Re-identification', 'Metric Learning']
categories: []
date: '2016-01-01'
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
publishDate: '2021-06-12T03:07:46.646226Z'
publication_types:
- '2'
abstract: 'Person reidentification, which matches person images of the same identity across nonoverlapping camera views, becomes an important component for cross-camera-view activity analysis. Most (if not all) person reidentification algorithms are designed based on appearance features. However, appearance features are not stable across nonoverlapping camera views under dramatic lighting change, and those algorithms assume that two cross-view images of the same person can be well represented either by exploring robust and invariant features or by learning matching distance. Such an assumption ignores the nature that images are captured under different camera views with different camera characteristics and environments, and thus, mostly there exists large discrepancy between the extracted features under different views. To solve this problem, we formulate an asymmetric distance model for learning camera-specific projections to transform the unmatched features of each view into a common space where discriminative features across view space are extracted. A cross-view consistency regularization is further introduced to model the correlation between view-specific feature transformations of different camera views, which reflects their nature relations and plays a significant role in avoiding overfitting. A kernel cross-view discriminant component analysis is also presented. Extensive experiments have been conducted to show that asymmetric distance modeling is important for person reidentification, which matches the concerns on cross-disjoint-view matching, reporting superior performance compared with related distance learning methods on six publically available data sets.'
publication: 'In *IEEE transactions on circuits and systems for video technology*'
url_code: 'publication/2016-chen-asymmetric/demo_CVDCA.zip'
links: 
- name: Feature
  url: "publication/2015-chen-mirror/demo_feat.zip"
---
