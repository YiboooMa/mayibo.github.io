---
title: "Mitigating Energy Consumption in Heterogeneous Mobile Networks through Data-Driven Optimization"
authors:
- admin
- Tong Li
- Yan Zhou
- Li Yu
- Depeng Jin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-06-18T00:00:00Z"
doi: "10.1109/TNSM.2024.3416947"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Network and Service Management (TNSM)*
publication_short: In *TNSM*

abstract: 5G networks, with their notable energy consumption, pose a significant challenge. Traditional energy-saving methods, effective for 4G, struggle in heterogeneous 4G and 5G networks. In this paper, we propose the pRoactivE Data-drivEn Energy Saving Method (REDEEM) to mitigate energy consumption in heterogeneous 4G and 5G mobile networks. REDEEM spatially divides the network into meshes based on cell overlaps, predicts cell traffic for proactive control, and selects active cells within each mesh. Our framework includes energy efficiency profiling for each mesh and offloads 5G traffic onto overlapping 4G cells to reduce 5G energy usage. Experiments based on the Nanchang mobile networks validate REDEEM’s effectiveness, yielding energy savings of 3442.72 MWh over a week. Notably, our approach achieves a 53.10% energy-saving rate, surpassing threshold-based methods by 38.85%, optimization-based methods by 18.15%, and fluid capacity engine by 14.79%. It minimally impacts service quality, with less than four parts per million traffic missed. Experimental results also demonstrate REDEEM’s robustness across various temporal, spatial, and traffic load scenarios.

# Summary. An optional shortened abstract.
summary: IEEE TNSM

tags:
  - Mobile Network
  - Data-Driven Energy Saving Method
  - 5G
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10565848
url_code: 'https://github.com/tsinghua-fib-lab/REDEEM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Framework overview of REDEEM.'
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