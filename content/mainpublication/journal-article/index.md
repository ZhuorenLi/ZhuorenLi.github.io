---
title: "An Integrated of Decision Making and Motion Planning Framework for Enhanced Oscillation-Free Capability"
authors:
- Zhuoren Li
- Jia Hu
- Bo Leng
- Lu Xiong
- Zhiqiang Fu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-11-23"
doi: "10.1109/TITS.2023.3332655"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Trans. Intell. Transp. Syst.*, early access"

abstract: "Autonomous driving requires efficient and safe decision making and motion planning in dynamic and uncertain environments. Future movement of surrounding vehicles is often difficult to represent. Besides, most existing studies consider decision making and planning/control separately. Both them may lead to the oscillation and unsafe for autonomous driving. This paper proposes an integrated framework of decision making and motion planning with oscillation-free capability. The proposed approach overcomes the shortcomings of autonomous driving for lane change/keeping maneuvers and is able to: i) make oscillation-free behavior decisions given biased prediction; ii) cut through in the traffic efficiently and safely when being in squeezed; iii) accelerate computation efficiency by building a state transfer model based on prediction uncertainty; iv) reduce the dissonance between decision-making and motion planning. A belief decision planner is designed with the uncertainty of the prediction trajectories. Lateral and longitudinal drivable corridors including the reference state and the related boundary constraints are built, which provide better suited information for planning to solve the optimal motion sequence more quickly and stably, and improve its consistency with decision module. Finally, the problem is formulated as an optimal control problem considering the vehicle dynamics and some soft constraints and the motion trajectory is solved by OSQP. Simulation and experimental tests are implemented to evaluate the feasibility and effectiveness of the proposed approach. Test results show that the integrated approach can make proper, safe and continuous decision and planning for autonomous vehicles and the calculation time is very low."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- POMDP
- optimization
featured: false

links:
- name: "PDF"
  url: uploads/paper.pdf # uploads/paper.pdf
#   url: ""
# url_pdf: https://ieeexplore.ieee.org/document/10328568
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: true

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
