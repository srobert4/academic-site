---
title: "An Open-Source Realtime Computation Platform (Short WIP Paper)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Pavan Mehrotra
- Sabar Dasgupta
- Samantha Robertson
- Paul Nuyujukian

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2018-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of 19th ACM SIGPLAN/SIGBED Conference on Languages, Compilers, and Tools for Embedded Systems (LCTES’18)
publication_short: In LCTES' 18

abstract: Systems neuroscience studies involving in-vivo models often require realtime data processing. In these studies, many events must be monitored and processed quickly, including behavior of the subject (e.g., movement of a limb) or features of neural data (e.g., a neuron transmitting an action potential). Unfortunately, most realtime platforms are proprietary, require specific architectures, or are limited to low-level programming languages. Here we present a hardware-independent, open-source realtime computation platform that supports high-level programming. The resulting platform, LiCoRICE, can process on order 10e10 bits/sec of network data at 1 ms ticks with 18.2 µs jitter. It connects to various inputs and outputs (e.g., DIO, Ethernet, database logging, and analog line in/out) and minimizes reliance on custom device drivers by leveraging peripheral support via the Linux kernel. Its modular architecture supports model-based design for rapid prototyping with C and Python/Cython and can perform numerical operations via BLAS/LAPACKoptimized NumPy that is statically compiled via Numba’s pycc. LiCoRICE is not only suitable for systems neuroscience research, but also for applications requiring closed-loop realtime data processing from robotics and control systems to interactive applications and quantitative financial trading.

# Summary. An optional shortened abstract.
summary: ""

tags: ["licorice", "neuroscience", "software", "realtime"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3211332.3211344'
url_code: 'http://github.com/bil/licorice'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
