---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Semi-supervised Monocular 3D Object Detection by Multi-view Consistency"
authors: 
- Qing Lian
- Yanbo Xu
- Weilong Yao
- admin
- Tong Zhang
tags: ['3D Vision']
categories: []
date: '2022-10-23'
featured: false
draft: false

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract: "The success of monocular 3D object detection highly relies on considerable labeled data, which is costly to obtain. To alleviate the annotation effort, we propose MVC-MonoDet, the first semi-supervised training framework that improves Monocular 3D object detection by enforcing multi-view consistency. In particular, a box-level regularization and an object-level regularization are designed to enforce the consistency of 3D bounding box predictions of the detection model across unlabeled multi-view data (stereo or video). The box-level regularizer requires the model to consistently estimate 3D boxes in different views so that the model can learn cross-view invariant features for 3D detection. The object-level regularizer employs an object-wise photometric consistency loss that mitigates 3D box estimation error through structure-from-motion (SFM). A key innovation in our approach to effectively utilize these consistency losses from multi-view data is a novel relative depth module that replaces the standard depth module in vanilla SFM. This technique allows the depth estimation to be coupled with the estimated 3D bounding boxes, so that the derivative of consistency regularization can be used to directly optimize the estimated 3D bounding boxes using unlabeled data. We show that the proposed semi-supervised learning techniques effectively improve the performance of 3D detection on the KITTI and nuScenes datasets. We also demonstrate that the framework is flexible and can be adapted to both stereo and video data."
publication: '*Proceedings of the European conference on computer vision (ECCV)*'
# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://link.springer.com/content/pdf/10.1007/978-3-031-20074-8.pdf"
url_code: "https://github.com/lianqing11/mvc_monodet"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
