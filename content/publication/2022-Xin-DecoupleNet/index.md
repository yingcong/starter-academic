---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "DecoupleNet: Decoupled Network for Domain Adaptive Semantic Segmentation"
authors: 
- Xin Lai
- Zhuotao Tian
- Xiaogang Xu
- admin
- Shu Liu
- Hengshuang Zhao
- Liwei Wang
- Jiaya Jia
tags: ['Semantic Segmentation', 'Domain Adaptation']
categories: []
date: '2022-10-23'
featured: false
draft: false

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]



abstract: "Unsupervised domain adaptation in semantic segmentation alleviates the reliance on expensive pixel-wise annotation. It uses a labeled source domain dataset as well as unlabeled target domain images to learn a segmentation network. In this paper, we observe two main issues of existing domain-invariant learning framework. (1) Being distracted by the feature distribution alignment, the network cannot focus on the segmentation task. (2) Fitting source domain data well would compromise the target domain performance. To address these issues, we propose DecoupleNet to alleviate source domain overfitting and let the final model focus more on the segmentation task. Also, we put forward Self-Discrimination (SD) and introduce an auxiliary classifier to learn more discriminative target domain features with pseudo labels. Finally, we propose Online Enhanced Self-Training (OEST) to contextually enhance the quality of pseudo labels in an online manner. Experiments show our method outperforms existing state-of-the-art methods. Extensive ablation studies verify the effectiveness of each component."
publication: '*Proceedings of the European conference on computer vision (ECCV)*'
# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'https://arxiv.org/pdf/2207.09988.pdf'
url_code: 'https://github.com/dvlab-research/DecoupleNet'
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
