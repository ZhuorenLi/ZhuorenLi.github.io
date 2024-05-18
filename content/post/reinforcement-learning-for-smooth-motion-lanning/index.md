---
title: Reinforcement Learning for Smooth Motion Planning
date: '2024-05-01'
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
**DRL directly control in stable and smooth performance**
- The output commands are easy to change continuously whent DRL agent directly generates the control command.
- The control commands generated in real-time are prone to sudden changes in dynamically changing environments due to the lack of long-term motion planning.

## **Highlights**
- Proposes a stability enhanced hierarchical reinforcement learning framework to achieve smooth and flexible driving behavior in dynamic traffic environment.
- Enables RL agent to participate in trajectory generation, where the trajectory parameter action is used to generate future motion path that adapt to various scenes.
- Realizes hybrid action output based on parameterized action space, hence the discrete and continuous actions have the optimal consistency.

<!-- ## **Published paper:**
1. Zhuoren Li, Lu Xiong, Bo Leng et.al. Safe Reinforcement Learning of Lane Change Decision Making with Risk-Fused Constraint, in Proc. IEEE Int. Conf. Intell. Transp. Syst. (ITSC), 2023, pp. 1313-1319. -->

## **Paper in Preparation:**
1. Guizhe Jin, Zhuoren Li, Bo Leng, Wie Han and Lu Xiong, "Stability Enhanced Hierarchical Reinforcement Learning for Autonomous Driving with Parameterized Trajectory Action." (under review in IEEE Int. Conf. Intell. Transp. Syst. (ITSC), 2024.)
