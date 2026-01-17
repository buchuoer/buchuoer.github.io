---
title: 'Wow, wo, val! A Comprehensive Embodied World Model Evaluation Turing Test'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chun-Kai Fan
  - Xiaowei Chi
  - Xiaozhu Ju
  - Hao Li
  - me
  - 'et al.'

# Author notes (optional)
author_notes: []

date: '2026-01-17T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-preprint']

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2601.04137*'
publication_short: '*arXiv*'

abstract: >-
  As **world models** gain momentum in **Embodied AI**, an increasing number of works explore using **video foundation models** as predictive world models for downstream embodied tasks like 3D prediction or interactive generation. However, before exploring these downstream tasks, video foundation models still have two critical questions unanswered: (1) whether their **generative generalization** is sufficient to maintain **perceptual fidelity** in the eyes of human observers, and (2) whether they are robust enough to serve as a **universal prior** for real-world embodied agents. To provide a standardized framework for answering these questions, we introduce the **Embodied Turing Test benchmark: WoW-World-Eval (Wow,wo,val)**. Building upon 609 robot manipulation data, **Wow-wo-val** examines five core abilities, including **perception, planning, prediction, generalization, and execution**. We propose a comprehensive evaluation protocol with **22 metrics** to assess the models’ generation ability, which achieves a high **Pearson Correlation** between the overall score and human preference (**>0.93**) and establishes a reliable foundation for the **Human Turing Test**. On **Wow-wo-val**, models achieve only **17.27** on **long-horizon planning** and at best **68.02** on **physical consistency**, indicating limited spatiotemporal consistency and physical reasoning. For the **Inverse Dynamic Model Turing Test**, we first use an **IDM** to evaluate the video foundation models’ execution accuracy in the real world. However, most models collapse to **≈ 0% success**, while **WoW** maintains a **40.74% success rate**. These findings point to a noticeable gap between the generated videos and the real world, highlighting the **urgency and necessity of benchmarking World Model in Embodied AI**.

# Summary. An optional shortened abstract.
summary: A comprehensive evaluation framework and Turing test for embodied world models, assessing metrics like video quality, physical law consistency, and execution accuracy.

tags:
  - World Model
  - Embodied AI
  - Evaluation
  - Turing Test

featured: true

hugoblox:
  ids:
    arxiv: '2601.04137'

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/wow-world-model/wow-world-model
  - icon: house
    icon_pack: fas
    name: Project Page
    url: https://wow-world-model.github.io/

url_pdf: 'https://arxiv.org/abs/2601.04137'
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
  caption: 'Metrics, Abilities, and Performance of Embodied World Models'
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

You can find the full paper and supplemental materials at the links above.
