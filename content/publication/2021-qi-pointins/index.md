---
title: "PointINS: Point-based instance segmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lu Qi
- Yi Wang
- Yukang Chen
- admin
- Xiangyu Zhang
- Jian Sun
- Jiaya Jia

# Author notes (optional)
author_notes:
- ""
- ""

date: "2021-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transation on Pattern Analysis and Machine Intelligence*
# publication_short: In *TPAMI*

abstract: In this paper, we explore the mask representation in instance segmentation with Point-of-Interest (PoI) features. Differentiating multiple potential instances within a single PoI feature is challenging, because learning a high-dimensional mask feature for each instance using vanilla convolution demands a heavy computing burden. To address this challenge, we propose an instance-aware convolution. It decomposes this mask representation learning task into two tractable modules as instance-aware weights and instance-agnostic features. The former is to parametrize convolution for producing mask features corresponding to different instances, improving mask learning efficiency by avoiding employing several independent convolutions. Meanwhile, the latter serves as mask templates in a single point. Together, instance-aware mask features are computed by convolving the template with dynamic weights, used for the mask prediction. Along with instance-aware convolution, we propose PointINS, a simple and practical instance segmentation approach, building upon dense one-stage detectors. Through extensive experiments, we evaluated the effectiveness of our framework built upon RetinaNet and FCOS. PointINS in ResNet101 backbone achieves a 38.3 mask mean average precision (mAP) on COCO dataset, outperforming existing point-based methods by a large margin. It gives a comparable performance to the region-based Mask R-CNN with faster inference.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Instance Segmentation']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'publication/qi2021pointins/2021-qi-pointins.pdf'
url_code: 'https://github.com/qqlu/PointINS'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
