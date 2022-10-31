---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Semiparametric expectile regression for high-dimensional heavy-tailed and heterogeneous data"
authors: []
date: "2019-08-18"
doi: "https://arxiv.org/abs/1908.06431"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-03T18:45:54+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Recently, high-dimensional heterogeneous data have attracted a lot of attention and discussion. Under heterogeneity, semiparametric regression is a popular choice to model data in statistics. In this paper, we take advantages of expectile regression in computation and analysis of heterogeneity, and propose the regularized partially linear additive expectile regression with nonconvex penalty, for example, SCAD or MCP for such high-dimensional heterogeneous data. We focus on a more realistic scenario: the regression error is heavy-tailed distributed and only has finite moments, which is violated with the classical sub-gaussian distribution assumption and more common in practise. Under some regular conditions, we show that with probability tending to one, the oracle estimator is one of the local minima of our optimization problem. The theoretical study indicates that the dimension cardinality of linear covariates our procedure can handle with is essentially restricted by the moment condition of the regression error. For computation, since the corresponding optimization problem is nonconvex and nonsmooth, we derive a two-step algorithm to solve this problem. Finally, we demonstrate that the proposed method enjoys good performances in estimation accuracy and model selection through Monto Carlo simulation studies and a real data example. What’s more, by taking different expectile weights α, we are able to detect heterogeneity and explore the entire conditional distribution of the response variable, which indicates the usefulness of our proposed method for analyzing high dimensional heterogeneous data."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1908.06431.pdf
url_code:
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
