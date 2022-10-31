---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "scReadSim: a single-cell RNA-seq and ATAC-seq read simulator"
event: "CMCF 2022 Annual Symposium on Multiscale Cell Fate"
event_url: https://cellfate.uci.edu/symposium-2022/
location:
address:
  street:
  city: Irvine
  region:
  postcode: 92697
  country: United States
summary:
abstract: "Rapid advances of single-cell RNA-seq and ATAC-seq technologies have propelled the development of many computational tools, benchmarking of which demands realistic simulators. However, few simulators can generate sequencing reads, and none of existing read simulators aim to mimic real cells, hindering the benchmarking of low-level computational tools that process reads. To fill this gap, we propose scReadSim, a single-cell RNA-seq and ATAC-seq read simulator that generates synthetic cells which mimic real cells. Trained on real data, scReadSim can generate synthetic data in FASTQ and BAM formats. By deploying scReadSim on sci-ATAC-seq and 10x Multiome (ATAC+RNA) data, we show that the scReadSim synthetic data resemble real data at both read and count levels. Moreover, as a flexible simulator, scReadSim enables users to arbitrarily specify open chromatin regions for the synthetic scATAC-seq reads, and is also capable of allowing varying the cell number and sequencing depths for the synthetic data.
To illustrate the versatile usage of scReadSim, we include two exemplar benchmark studies to show that scReadSim provides unique molecular identifier (UMI) counts for benchmarking scRNA-seq deduplication tools and can accommodate user-specified open chromatin regions (``ground truths'') to generate single-cell ATAC-seq data. Our benchmark applications of scReadSim show that cellranger is a preferred scRNA-seq deduplication tool, and MACS3 achieves top performance in scATAC-seq peak calling."


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-10-25T15:00:00+08:00
#date_end: 2020-08-03T16:21:21+08:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-08-03T16:21:21+08:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "CMCF 2022 Annual Symposium on Multiscale Cell Fate"
  focal_point: "Right"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: slides.pdf

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
