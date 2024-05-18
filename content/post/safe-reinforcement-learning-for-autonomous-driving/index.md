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

## **Motivation**
**Limitation in Safety Performance**
Deep reinforcement learning (DRL) has become a powerful method for autonomous driving while often lacking safety guarantees.

## **Highlights**
- Evaluate the future motion risk by projecting DRL behavior action into the feasible trajectory, while sorrunding vehicles' trajecotires are obtained from the prediction module.
- Dangerous action will be prevented and the dangerous virtual experiences are recoreded to gain various valuable experience data.
- Dangerous experiences are sampled with priority weight according their anticipated risk, enabling DRL agnet to learn a safer policy.

## **Published paper:**
1. Zhuoren Li, Lu Xiong, Bo Leng et.al. Safe Reinforcement Learning of Lane Change Decision Making with Risk-Fused Constraint, in Proc. IEEE Int. Conf. Intell. Transp. Syst. (ITSC), 2023, pp. 1313-1319.

## **Paper in Preparation:**
1. Zhuoren Li, Jia Hu, Bo Leng, Lu Xiong, et.al. Safety Enhanced Reinforcement Learning for Autonomous Driving: Dare to Make Mistakes to Learn Faster and Better. (Preparing to submit IEEE Trans. Transp. Electrif.)
2. Ruolin Yang, Zhuoren Li, Bo Leng, et.al. Convergent Harmonious Decision: Lane Changing in a more Traffic Friendly Way. (under review of IEEE Trans. Intell. Vehicles)