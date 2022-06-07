---
title: "Safe Real-world HVAC Control via Batch Reinforcement Learning"
collection: publications
permalink: /publication/Safe-Real-world-HVAC-Control-via-Batch-Reinforcement-Learning
date: 2022-05-04
venue: 'International Conference on Cyber-Physical Systems (ICCPS)'
paperurl: 'https://conferences.computer.org/cpsiot/pdfs/ICCPS2022-ifhdJu28kaMK8qGYbf7d0/096700a181/096700a181.pdf'
citation: 
---
![Framework Setup](/images/Safe_HVAC_flow_chart.png)

Buildings account for 30% of energy use worldwide, and approximately half of it is ascribed to HVAC systems. 
Reinforcement Learning (RL) has improved upon traditional control methods in increasing the energy efficiency of HVAC systems. However, prior works
use online RL methods that require configuring complex thermal
simulators to train or use historical data-driven thermal models that
can take at least 10^4 time steps to reach rule-based performance.  

Also, due to the distribution drift from simulator to real buildings,
RL solutions are therefore seldom deployed in the real world. On
the other hand, batch RL methods can learn from the historical
data and improve upon the existing policy without any interactions
with the real buildings or simulators during the training.  

With the existing rule-based policy as the priors, the policies learned with
batch RL are better than the existing control from the first day of
deployment with very few training steps compared with online
methods.  

Our algorithm incorporates a Kullback-Leibler (KL) regularization term to penalize policies that deviate far from the previous
ones. We evaluate our framework on a real multi-zone, multi-floor
building—it achieves 7.2% in energy reduction cf. the state-of-the-art batch RL method, and outperforms other BRL methods in occupants’ thermal comfort, and 16.7% energy reduction compared to
the default rule-based control.