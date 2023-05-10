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

I am a Ph.D. candidate at University of California San Deigo (UCSD).  
My PI is [Professor Rajesh K. Gupta](http://mesl.ucsd.edu/gupta/),  
our lab is [Microelectronic Embedded Systems Laboratory (MESL)](http://mesl.ucsd.edu/).  
My research focus is Deep Reinforcement Learning methodology improvement and its application in real-world problems.


Research focus
======
* **Batch Reinforcement Learning (Offline RL)**
![Offline Reinforcement Learning](https://offline-rl.github.io/assets/OFFLINE_RL.gif | width=50)

Agarwal, R., Schuurmans, D. & Norouzi, M.. (2020). An Optimistic Perspective on Offline Reinforcement Learning International Conference on Machine Learning (ICML).



Projects 
======
* **Offline-RL Regularization (Papers published in NeurIPS Offline-RL Workshop 2021 and ICCPS 2022)**
  * Batch-RL (BRL) method needs no simulator, only prior transitions as replay buffer to learn the optimal policy. 
  Our Batch-Constrained Munchausen Q-learning (BCM) outperforms other BRL methods in real building multi-zone environments 
  during weeks of evaluation time period. It maximizes the energy efficiency and the occupants’ thermal comfort simultaneously.

* **Incorporting Existing Policy with RL (Paper to appear in e-Energy 2023)**
  * We incorporate existing rule-based control (RBC) policy with RL to improve the robustness and stability. It is an unified
  method to be added in both online and offline methods.

* **Open-sourced Building BRL dataset (Paper published in BuildSys' 22 RLEM)**
  * We are the first to open-source the building HVAC control dataset for BRL benchmark. With one dataset of real-building control
  and sensing data, and the other one generated with simulation environments. The benchmark results are also included.

* **Offline-to-Online RL (Submitted to incoming ML conference)**
  * Pre-trained non-expert BRL models are expected to increase their averaged sampled Q-value during the training. We develop
  a method to let the policy learns to yield a higher average Q-value over time. Our method outperforms SOTA methods with better
  initial and final scores during evaluations.


Misc.
======
I enjoy heavy metal music, [baseball (Go! Padres!)](/images/padres.jpeg), [hiking](/images/mountain.png), and [exploring nature](/images/white_sand.jpeg).