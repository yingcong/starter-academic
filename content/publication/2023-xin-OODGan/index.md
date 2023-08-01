---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Photo-Realistic Out-of-domain GAN inversion via Invertibility Decomposition"
subtitle: ''
summary: ''
authors:
- Xin Yang
- Xiaogang Xu
- admin
tags: ['Generative Adversarial Networks', 'Face Manipulation', 'Image-to-image Translation']
categories: []
categories: []
date: '2023-06-19'
lastmod: 2023-06-19T11:07:49+08:00
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
publishDate: '2023-06-19T03:07:48.919569Z'
publication_types:
- '2'
abstract: "The fidelity of Generative Adversarial Networks (GAN) inversion is impeded by Out-Of-Domain (OOD) areas (e.g., background, accessories) in the image. Detecting the OOD areas beyond the generation ability of the pre-trained model and blending these regions with the input image can enhance fidelity. The ``invertibility mask'' figures out these OOD areas, and existing methods predict the mask with the reconstruction error. However, the estimated mask is usually inaccurate due to the influence of the reconstruction error in the In-Domain (ID) area. In this paper, we propose a novel framework that enhances the fidelity of human face inversion by designing a new module to decompose the input images to ID and OOD partitions with invertibility masks. Unlike previous works, our invertibility detector is simultaneously learned with a spatial alignment module. We iteratively align the generated features to the input geometry and reduce the reconstruction error in the ID regions. Thus, the OOD areas are more distinguishable and can be precisely predicted. Then, we improve the fidelity of our results by blending the OOD areas from the input image with the ID GAN inversion results. Our method produces photo-realistic results for real-world human face image inversion and manipulation. Extensive experiments demonstrate our method's superiority over existing methods in the quality of GAN inversion and attribute manipulation."
publication: 'In *Proceedings of the IEEE International Conference on Computer Vision (ICCV)*'
url_code: 'https://github.com/AbnerVictor/OOD-GAN-inversion'
# url_video: ''
# url_project: 

---
