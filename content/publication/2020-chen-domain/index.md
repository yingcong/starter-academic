---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Domain Adaptive Image-to-image Translation
subtitle: ''
summary: ''
authors:
- admin
- Xiaogang Xu
- Jiaya Jia
tags: ['Image-to-image Translation', 'Domain Adaptation', 'Face Manipulation', 'Generative Adversarial Networks']
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
publishDate: '2021-06-12T03:07:48.228655Z'
publication_types:
- '1'
abstract: 'Unpaired image-to-image translation (I2I) has achieved great success in various applications. However, its generalization capacity is still an open question. In this paper, we show that existing I2I models do not generalize well for samples outside the training domain. The cause is twofold. First, an I2I model may not work well when testing samples are beyond its valid input domain. Second, results could be unreliable if the expected output is far from what the model is trained. To deal with these issues, we propose the Domain Adaptive Image-To-Image translation (DAI2I) framework that adapts an I2I model for out-of-domain samples. Our framework introduces two sub-modules -- one maps testing samples to the valid input domain of the I2I model, and the other transforms the output of I2I model to expected results. Extensive experiments manifest that our framework improves the capacity of existing I2I models, allowing them to handle samples that are distinctively different from their primary targets.
'
publication: '*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition*'
url_pdf: 'https://openaccess.thecvf.com/content_CVPR_2020/html/Chen_Domain_Adaptive_Image-to-Image_Translation_CVPR_2020_paper.html'
url_video: 'publication/2020-chen-domain/DAI2I.mp4'
---
