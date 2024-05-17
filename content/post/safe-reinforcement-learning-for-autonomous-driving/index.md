---
title: Safe Reinforcement Learning for Autonomous Driving
date: '2023-09-01'
# date_format: Jan 2006
# date_start: '2022-09-01'
# date_end: ''
# summary: from 2021.09 - Now
---

<!-- code mode
```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
``` -->

<!-- ![png](SRL-Framework.png)     -->

## Limitation in Safety Performance

Deep reinforcement learning (DRL) has become a powerful method for autonomous driving while often lacking safety guarantees.

## Import the notebooks into your site

We map the decision action to the trajectory layer via a polynomial curve-based trajectory planner, which is combined with the predicted trajectories of surrounding vehicles to evaluate the future risk and correct the unsafe action.

**Published paper:**
Zhuoren Li, Lu Xiong, Bo Leng et.al. Safe Reinforcement Learning of Lane Change Decision Making with Risk-Fused Constraint, in Proc. IEEE Int. Conf. Intell. Transp. Syst. (ITSC), 2023, pp. 1313-1319.

**Paper in Preparing:**
Zhuoren Li, Jia Hu, Bo Leng, Lu Xiong, et.al. Safety Enhanced Reinforcement Learning for Autonomous Driving: Dare to Make Mistakes to Learn Faster and Better. (Preparing to submit IEEE Trans. Transp. Electrif.)