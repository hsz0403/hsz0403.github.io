---
title: 'ActFormer: Scalable Collaborative Perception via Active Queries'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
[Suozhi Huang*,Juexiao Zhang*,Yiming Li,Chen Feng]
# author:
#   - suozhi
#   - Juexiao Zhang*
#   - Yiming Li 
#   - Chen Feng
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
#   -
#   -

date: '2024-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICRA 2024*
publication_short: In *ICRA 2024*

abstract: We present ActFormer, a Transformer that learns
  bird’s eye view (BEV) representations by using predefined BEV
  queries to interact with multi-robot multi-camera inputs. Each
  BEV query can actively select relevant cameras for information
  aggregation based on pose information, instead of interacting
  with all cameras indiscriminately. Experiments on the V2X-Sim
  dataset demonstrate that ActFormer improves the detection
  performance from 29.89% to 45.15% in terms of AP@0.7
  with about 50% fewer queries, showcasing the effectiveness
  of ActFormer in multi-agent collaborative 3D object detection.

# Summary. An optional shortened abstract.
summary: In this work, we aim to address scalable
  camera-based collaborative perception with a Transformer-based
  architecture.

tags:
  - Computer Vision
  - Robotics


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2403.04968'
url_code: 'https://github.com/coperception/ActFormer'
url_dataset: ''
url_poster: ''
url_project: 'https://coperception.github.io/ActFormer/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=grvPVxIKfDE&feature=youtu.be'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
