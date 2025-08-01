---
title: "BIRF-SDG: Band Importance Aware Random Frequency Filter Based Single-Source Domain Generalization for Retinal Vessel Segmentation"
authors:
- admin
date: "2025-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Single-source domain generalization (SDG) is used to improve model’s performance on unseen target domains by utilizing data from one source domain, with a primary emphasis on alleviating the impact of domain shifts. In the context of retinal vessel segmentation, domain shifts often arise due to variations in datasets composition, such as discrepancies in disease prevalence and imaging noise levels. Despite their significance, the underlying mechanisms through which these shifts impact model performance remain insufficiently explored. In this paper, we hypothesize that dataset variations are reflected in the distributional differences of frequency-domain features, which can cause models to overfit to specific patterns within the source dataset. To address the problem, this paper proposes a novel SDG method, denoted as Band Importance Aware Random Frequency Filter based Single-source Domain Generalization (BIRF-SDG). This framework incorporates a band scoring mechanism designed to identify and preserve frequency bands that are critical for segmentation tasks, thereby preventing the loss of essential information in subsequent processes. Furthermore, we propose a random band filtering strategy as a data augmentation technique to improve the model's generalization across various domains. Extensive comparative experiments and ablation analyses on cross-domain retinal image datasets confirm that our method attains state-of-the-art performance, effectively addressing the challenges associated with domain shift in retinal vessel segmentation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Segmentation

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://link.springer.com/chapter/10.1007/978-981-95-0036-9_23
url_code: 'https://github.com/aurora324/BIRF-SDG'
url_dataset: 'https://drive.grand-challenge.org/'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](uploads/BIRF-SDG.png)'
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
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
