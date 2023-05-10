---
title: "Rule-based Policy Regularization for Reinforcement Learning-based Building Control"
collection: publications
permalink: /publication/Rule-based-Policy-Regularization-for-Reinforcement-Learning-based-Building-Control
date: 2023-06-20
venue: 'The 14th ACM International Conference on Future Energy Systems (ACM e-Energy 2023)'
paperurl: 
citation:
---
![RUBICON Flow](/images/RUBICON.png)

Rule-based control (RBC) is widely adopted in buildings due to its
stability and robustness. It resembles a behavior cloning methodology
refined by human experts; however, it is incapable of adapting
to distribution drifts. Reinforcement learning (RL) can adapt to
changes but needs to learn from scratch in the online setting. On
the other hand, the learning ability is limited in offline settings
due to extrapolation errors caused by selecting out-of-distribution
actions. In this paper, we explore how to incorporate RL with a rulebased
control policy to combine their strengths to continuously
learn a scalable and robust policy in both online and offline settings.
We start with representative online and offline RL methods, TD3 and
TD3+BC, respectively. Then, we develop a dynamically weighted
actor loss function to selectively choose which policy for RL models
to learn from at each training iteration. With extensive experiments
across various weather conditions in both deterministic and stochastic
scenarios, we demonstrate that our algorithm, rule-based
incorporated control regularization (RUBICON), outperforms stateof-
the-art methods in offline settings by 40.7% and improves the
baseline method by 49.7% in online settings with respect to a reward
consisting of thermal comfort and energy consumption in
building-RL environments.