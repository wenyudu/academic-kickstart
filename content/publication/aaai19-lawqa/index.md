---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Multi-Task Learning Approach for Answer Selection: A Study and a Chinese Law Dataset"
authors: [Wenyu Du, Baocheng Li, Min Yang, Qiang Qu, Ying Shen]
date: 2019-01-10T20:05:52+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-01-10T20:05:52+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 33rd AAAI Conference on Artificial Intelligence"
publication_short: "AAAI, student abstract"

abstract: "In this paper, we propose a Multi-Task learning approach for Answer Selection (MTAS), motivated by the fact that humans have no difficulty performing such task because they possess capabilities of multiple domains (tasks). Specifically, MTAS consists of two key components: (i) A category classification model that learns rich category-aware document representation; (ii) An answer selection model that provides the matching scores of question-answer pairs. These two tasks work on a shared document encoding layer, and they cooperate to learn a high-quality answer selection system. In addition, a multi-head attention mechanism is proposed to learn important information from different representation subspaces at different positions. We manually annotate the first Chinese question answering dataset in law domain (denoted as LawQA) to evaluate the effectiveness of our model. The experimental results show that our model MTAS consistently outperforms the compared methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [Question Answering, Dataset Paper, NLP]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: Full Version
   url: publication/cqa_full.pdf
   icon_pack: fab
   icon: 

url_pdf: https://www.aaai.org/ojs/index.php/AAAI/article/view/5104
url_code: https://github.com/ange1o/mtas-lawqa
url_dataset:
url_poster: publication/aaai19_poster.pdf
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
