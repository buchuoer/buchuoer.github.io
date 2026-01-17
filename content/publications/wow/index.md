---
title: 'WoW: Towards a World omniscient World model Through Embodied Interaction'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaowei Chi
  - Peidong Jia
  - Chun-Kai Fan
  - me
  - 'et al.'

# Author notes (optional)
author_notes: []

date: '2025-09-22T00:00:00Z'

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-preprint']

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2509.22642*'
publication_short: '*arXiv*'

abstract: >-
  Humans develop an understanding of **intuitive physics** through active interaction with the world. This approach is in stark contrast to current video models, such as Sora, which rely on passive observation and therefore struggle with grasping **physical causality**. This observation leads to our central hypothesis: **authentic physical intuition of world model must be grounded in extensive, causally rich interactions with the real world**. To test this hypothesis, we present **WoW**, a **14B-parameter generative world model** trained on **2 million robot interaction trajectories**. Our findings reveal that the model’s understanding of physics is a **probabilistic distribution of plausible outcomes**, leading to stochastic instabilities and physical hallucinations. Furthermore, we demonstrate that this emergent capability can be actively constrained toward **physical realism** by **SOPHIA**, where vision language model agents evaluate the DiT’s generated output and guide its refinement by iteratively evolving the language instruction. Besides, a co-trained **Inverse Dynamics Model** translates these refined plans into executable robotic actions, thus closing the **imagination-to-action loop**. We establish **WoWBench**, a new benchmark focused on **physical consistency** and **causal reasoning of video**, where WoW achieves state-of-the-art performance of both human and autonomous evaluation, demonstrating strong ability on **physical causality**, **collision dynamics**, and **object permanence**. Our work provides the systematic evidence that **large-scale, realworld interaction** is a cornerstone for developing physical intuition in AI.

# Summary. An optional shortened abstract.
summary: World model trained on 2M real robot interactions demonstrating physical consistency, causal reasoning in video, and real-world robotic execution.

tags:
  - World Model
  - Embodied AI
  - Multimodal Large Language Models (MLLMs)
  - Robotic Interaction

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.48550/arXiv.2509.22642

# Custom links
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/wow-world-model/wow-world-model
  - icon: house
    icon_pack: fas
    name: Project Page
    url: https://wow-world-model.github.io/

url_pdf: 'wow.pdf'
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
  caption: 'WoW: Perception, Prediction, Judgement, Reflection, Action'
  focal_point: ''
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
