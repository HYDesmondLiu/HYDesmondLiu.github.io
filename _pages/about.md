---
permalink: /
title: "Hsin-Yu Liu's Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}

About me
======
![UCSD](https://upload.wikimedia.org/wikipedia/en/4/44/University_of_California%2C_San_Diego_seal.svg){: style="float: right"}  

I am a Ph.D. student at University of California San Deigo (UCSD).  
My PI is [Professor Rajesh K. Gupta](http://mesl.ucsd.edu/gupta/),  
our lab is [Microelectronic Embedded Systems Laboratory (MESL)](http://mesl.ucsd.edu/).  
My research focus is Batch/Offline Deep Reinforcement Learning and its applications.

Research focus
======
![Offline Reinforcement Learning](https://offline-rl.github.io/assets/OFFLINE_RL.gif)

* **Rule-based policy regularization for reinforcement learning-based building control (Submitted to ICLR 2023)**
  * Rule-based control (RBC) is widely adopted in buildings due to its stability and robustness. It resembles a behavior cloning methodology refined by human expertise. However, it is unlikely for RBC to exceed a reinforcement learning (RL) agent’s performance as deep RL model constantly evolves and is scalable. In this paper, we explore how to incorporate rule-based control into reinforcement learning to learn a more robust policy in both online and offline settings with a unified
approach. We start with state-of-the-art online and offline RL methods, TD3 and
TD3+BC, then improve on them using a dynamically weighted actor loss function to selectively choose which policy RL models to learn from at each time step
of training. With experiments across various weather conditions in both deterministic and stochastic scenarios, we empirically demonstrate that our rule-based
incorporated control regularization (RUBICON) method outperforms representative baseline methods in offline settings by 40.7% and by 49.7% in online settings
for building-RL environments.  

* **Offline-RL Regularization**
  * Batch-RL (BRL) method needs no simulator, only prior transitions as replay buffer to learn the optimal policy. 
  Our Batch-Constrained Munchausen Q-learning (BCM) outperforms other BRL methods in real building multi-zone environments 
  during weeks of evaluation time period. It maximizes the energy efficiency and the occupants’ thermal comfort simultaneously.

Misc.
======
I enjoy heavy metal music, [baseball (Go! Padres!)](/images/padres.jpeg), [hiking](/images/mountain.png), and [exploring nature](/images/white_sand.jpeg).