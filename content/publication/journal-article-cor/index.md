---
# Title of the publication
title: "A multi-start local search heuristic for the Green Vehicle Routing Problem based on a multigraph reformulation"

# Date first published
date: "2019-04-18"

# Schedule page publish date (NOT publication's date).
# publishDate: "2019-04-18T00:00:00Z"

# Authors, comma separated list
authors: ["Juho Andelmin", "Enrico Bartolini"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types: "2"

# DOI of the article
doi: "https://doi.org/10.1016/j.cor.2019.04.018"

# Publication name and optional abbreviated publication name.
publication: "In *Computers & Operations Research*"
publication_short: "In *COR*"

# Abstract 
abstract: "We consider the Green Vehicle Routing Problem (G-VRP) which is an extension of the classical vehicle routing problem for alternative fuel vehicles. In the G-VRP, vehicles’ driving autonomy and possible refueling stops en-route are explicitly modeled. We propose a multi-start local search algorithm that consists of three phases. The first two phases iteratively construct new solutions, improve them by local search, and store all vehicle routes forming these solutions in a route pool. Phase three optimally combines vehicle routes in the route pool by solving a set partitioning problem and improves the final solution by local search. The algorithm is based on a multigraph reformulation of the G-VRP in which nodes correspond to customers and a depot, and arcs correspond to possible sequences of refueling stops for vehicles traveling between two nodes. All local search operators used by our algorithm are tailored to exploit this reformulation and do not explicitly deal with refueling stations. We report computational results on benchmark instances with up to ∼ 470 customers, showing that the algorithm is competitive with state-of-the-art heuristics."

# Optional shortened abstract
summary: "We (i) consider the Green Vehicle Routing Problem (G-VRP) which adapts the classical vehicle routing problem to alternative fuel vehicles; (ii) propose a new multi-start local search matheuristic for the G-VRP which is based on a multigraph reformulation; (iii) demonstrate the effectiveness of our algorithm by comparing it to the other state of the art heuristic methods on a set of benchmark instances with up to 500 customers, and (iv) report improved best known upper bounds on 8 of the largest benchmark instances and show that our algorithm gives upper bounds that are on average within 0.27% far from optimal on a set of new benchmark instances with 50–100 customers."

# Summary. An optional shortened abstract.
# summary = Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# Featured image thumbnail (optional)
image_preview: ""

# Is this a selected publication? (true/false)
selected: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects: []

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Links (optional).
url_pdf:  ""
url_preprint: ""
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Custom links (optional)
# - name: ""
#    url: ""

# Does the content use math formatting?
math: true

# Does the content use source code highlighting?
highlight: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
#  focal_point = ""
#  preview_only = false

# tags:
# - Source Themes
# featured = false

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

Further details can be written here.
