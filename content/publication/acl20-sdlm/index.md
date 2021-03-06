---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploiting Syntactic Structure for Better Language Modeling: A Syntactic Distance Approach"
authors: [Wenyu Du*, Zhouhan Lin*, Yikang Shen, Timothy J. O'Donnell, Yoshua Bengio, Yue Zhang]
date: 2020-04-10T20:06:41+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-10T20:06:41+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 58th annual meeting of the Association for Computational Linguistics"
publication_short: "ACL, long"

abstract: "It is commonly believed that knowledge of syntactic structure should improve language modeling. However, effectively and computationally efficiently incorporating syntactic structure into neural language models has been a challenging topic. In this paper, we make use of a multi-task objective, i.e., the models simultaneously predict words as well as ground truth parse trees in a form called ''syntactic distances'', where information between these two separate objectives shares the same intermediate representation.  Experimental results on the Penn Treebank and Chinese Treebank datasets show that when ground truth parse trees are provided as additional training signals, the model is able to achieve lower perplexity and induce trees with better quality."

# Summary. An optional shortened abstract.
summary: ""

tags: [Language Modeling, NLP]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2005.05864
url_code: https://github.com/wenyudu/SDLM
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
