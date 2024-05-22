---
title: 'Safe Reinforcement Learning of Lane Change Decision Making with Risk-Fused Constraint'
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhuoren Li
  - Bo Leng 
  - Lu Xiong
  - Puhang Xu
  - Zhiqiang Fu
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-24'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "in Proc. *IEEE Int. Conf. Intell. Transp. Syst. (ITSC)*, 2023, pp. 1313-1319."

abstract: Deep reinforcement learning (DRL) has become a powerful method for autonomous driving while often lacking safety guarantees. In this paper, we propose a Risk-fused Constraint Deep Reinforcement Learning (RCDRL) with D3QN network for safe decision making in lane change maneuver. The problem is formulated as a state-wise MDP (SCMDP), which embeds a rule-based risk-fused Constraint module. We map the decision action to the trajectory layer via a polynomial curve-based trajectory planner, which is combined with the predicted trajectories of surrounding vehicles to assess future risk and correct the unsafe action. Therefore, the proposed method can deal with unsafe decision actions when training the policy network. To investigate the decision performance, the trained RCDRL policy is tested and validated under different traffic densities. In particular, we implement real vehicle tests to validate the effectiveness of the proposed method. Simulation and real vehicle tests demonstrated that the proposed RCDRL method achieves better performance, especially in safe decision. In addition, the framework can be extended with other advanced DRL networks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- Reinforcement Learning
- Safety
- Risk Evaluation

# Display this page in the Featured widget?
featured: flase

# Custom links (uncomment lines below)
links:
- name: "PDF"
  url: Safe_Reinforcement_Learning_of_Lane_Change_Decision_Making_with_Risk-Fused_Constraint.pdf
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


