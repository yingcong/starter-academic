---
title: "Text-Guided Human Image Manipulation via Image-Text Shared Space"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiaogang Xu
- admin
- Xin Tao
- Jiaya Jia

# Author notes (optional)
author_notes:
- ""
- "Corresponding Author"

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

abstract: Text is a new way to guide human image manipulation. Albeit natural and flexible, text usually suffers from inaccuracy in spatial description, ambiguity in the description of appearance, and incompleteness. We in this paper address these issues. To overcome inaccuracy, we use structured information (e.g., poses) to help identify correct location to manipulate, by disentangling the control of appearance and spatial structure. Moreover, we learn the image-text shared space with derived disentanglement to improve accuracy and quality of manipulation, by separating relevant and irrelevant editing directions for the textual instructions in this space. Our model generates a series of manipulation results by moving source images in this space with different degrees of editing strength. Thus, to reduce the ambiguity in text, our model generates sequential output for manual selection. In addition, we propose an efficient pseudo label loss to enhance editing performance when the text is incomplete. We evaluate our method on various datasets and show its precision and interactiveness to manipulate human images.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Generative Adversarial Networks', 'Multimodal', 'Text-guided Synthesis']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'publication/xu2021text/xu2021text.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
