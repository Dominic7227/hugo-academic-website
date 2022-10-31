---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "scReadSim: a single-cell RNA-seq and ATAC-seq read simulator"
authors:
- admin
- Jingyi Jessica Li
date: "2022-05-31"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-03T18:46:16+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*bioRxiv*"
publication_short: ""

abstract: "Rapid advances of single-cell RNA-seq and ATAC-seq technologies have propelled the development of many computational tools, benchmarking of which demands realistic simulators. However, few simulators can generate sequencing reads, and none of existing read simulators aim to mimic real cells, hindering the benchmarking of low-level computational tools that process reads. To fill this gap, we propose scReadSim, a single-cell RNA-seq and ATAC-seq read simulator that generates synthetic cells which mimic real cells. Trained on real data, scReadSim can generate synthetic data in FASTQ and BAM formats. By deploying scReadSim on sci-ATAC-seq and 10x Multiome (ATAC+RNA) data, we show that the scReadSim synthetic data resemble real data at both read and count levels. Moreover, as a flexible simulator, scReadSim enables users to arbitrarily specify open chromatin regions for the synthetic scATAC-seq reads, and is also capable of allowing varying the cell number and sequencing depths for the synthetic data.
To illustrate the versatile usage of scReadSim, we include two exemplar benchmark studies to show that scReadSim provides unique molecular identifier (UMI) counts for benchmarking scRNA-seq deduplication tools and can accommodate user-specified open chromatin regions (``ground truths'') to generate single-cell ATAC-seq data. Our benchmark applications of scReadSim show that cellranger is a preferred scRNA-seq deduplication tool, and MACS3 achieves top performance in scATAC-seq peak calling."

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

url_pdf: https://www.biorxiv.org/content/10.1101/2022.05.29.493924v1
url_code: https://github.com/JSB-UCLA/scReadSim
url_dataset:
url_poster:
url_project: https://screadsim.readthedocs.io/en/latest/
url_slides:
url_source: https://www.biorxiv.org/content/10.1101/2022.05.29.493924v1
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Icon of scReadSim"
  focal_point: "Left"
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
