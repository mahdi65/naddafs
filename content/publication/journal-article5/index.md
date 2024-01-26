---
title: "Deep Bayesian-Assisted Keypoint Detection for Pose Estimation in Assembly Automation"
authors:
- Debo Shi
- Alireza Rahimpour
- Amin Ghafourian
- M-Mahdi Naddaf-Sh
- Devesh Upadhyay
- Ty A Lasky
- Iman Soltani
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-07-02T00:00:00Z"
doi: "10.3390/s23136107"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Journal"]

# Publication name and optional abbreviated publication name.
publication: "Sensors"
publication_short: ""

abstract: Pose estimation is crucial for automating assembly tasks, yet achieving sufficient accuracy for assembly automation remains challenging and part-specific. This paper presents a novel, streamlined approach to pose estimation that facilitates automation of assembly tasks. Our proposed method employs deep learning on a limited number of annotated images to identify a set of keypoints on the parts of interest. To compensate for network shortcomings and enhance accuracy we incorporated a Bayesian updating stage that leverages our detailed knowledge of the assembly part design. This Bayesian updating step refines the network output, significantly improving pose estimation accuracy. For this purpose, we utilized a subset of network-generated keypoint positions with higher quality as measurements, while for the remaining keypoints, the network outputs only serve as priors. The geometry data aid in constructing likelihood functions, which in turn result in enhanced posterior distributions of keypoint pixel positions. We then employed the maximum a posteriori (MAP) estimates of keypoint locations to obtain a final pose, allowing for an update to the nominal assembly trajectory. We evaluated our method on a 14-point snap-fit dash trim assembly for a Ford Mustang dashboard, demonstrating promising results. Our approach does not require tailoring to new applications, nor does it rely on extensive machine learning expertise or large amounts of training data. This makes our method a scalable and adaptable solution for the production floors.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/1424-8220/23/13/6107
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
