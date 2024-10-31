---
title: "InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems"
authors:
 - Zijian Wu*
 - admin*
 - Zhejian Zhou
 - Huaiyuan Ying
 - Jiayu Wang
 - Dahua Lin
 - Kai Chen
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2024-10-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2023-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*Tech Report*"
publication_short: "*Tech Report*"

abstract: We propose to use large scale LEAN problem datasets Lean-workbook for expert iteration with more than 20,000 CPU days. During expert iteration, we found log-linear trends between solved problem amount with proof length and CPU usage. We train a critic model to select relatively easy problems for policy models to make trials and guide the model to search for deeper proofs. InternLM2.5-StepProver achieves open-source state-of-the-art on MiniF2F, Lean-Workbook-Plus, ProofNet, and Putnam benchmarks. Specifically, it achieves a pass of 65.9% on the MiniF2F-test and proves (or disproves) 17.0% of problems in Lean-Workbook-Plus which shows a significant improvement compared to only 9.5% of problems proved when Lean-Workbook-Plus was released.

# Summary. An optional shortened abstract.
summary: InternLM2.5-StepProver and its critic, setting a new minif2f SOTA at 65.9%. No hallucination, verified math proofs by LLM reasoning. 

tags:
- Large Language Models
- Formal Math
- Theorem Proving

featured: true

# links:
# # - name: Custom Link
# #   url: https://arxiv.org/abs/2410.15700
url_pdf: https://arxiv.org/abs/2410.15700
url_code: 'https://github.com/InternLM/InternLM-Math'
url_dataset: 'https://huggingface.co/datasets/internlm/Lean-Workbook'
url_poster: ''
url_project: 'https://github.com/InternLM/InternLM-Math'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

slides: ""
---

<!--  This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
