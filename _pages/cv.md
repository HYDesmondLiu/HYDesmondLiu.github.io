---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Education
======
University of California, San Diego — Ph.D. in Computer Engineering 
National Taiwan University — M.S. in Optoelectronics
National Central University — B.S. in Physics

Work experience
======
* *Apr. 2025 ~ Now: Applied AI Researcher*
  * **Articul8 AI (Remote / Dublin, CA)**
    * Improving hardware coding domain-specific models and benchmarks; post-training RL, synthetic data generation, and reinforcement-learning based personalization.

* *May 2024 ~ Apr. 2025: Machine Learning Engineer II*
  * **Glidewell Dental (Irvine, CA)**
    * Designed an Offline RL-based Next-Best-Action recommendation system and LLM RAG pipelines for unstructured documents; 2D-to-3D reconstruction projects for manufacturing.

* *Sep. 2018 ~ Jun. 2024: Graduate Student Researcher*
  * **University of California - San Diego (La Jolla, CA, USA)**
    * Research on online/offline/offline-to-online reinforcement learning, policy regularization, and RL for building HVAC control. Released open-source building batch RL datasets and published related work (Ph.D. dissertation Jun. 2024).

* *Jun. 2020 ~ Aug. 2020: Machine Learning Software Intern*
  * **Cadence Design Systems (Milpitas, CA)**
    * Developed and deployed clustering and partitioning algorithms for EDA performance and area optimization.

* *Oct. 2013 ~ Jul. 2018: Principal Application Engineer*
  * **Cadence Design Systems (Hsinchu, Taiwan)**
    * Built custom GUIs/scripts (Python, SKILL), supported customers, and collaborated with R&D on performance and feature improvements.

* *Nov. 2008 ~ Sep. 2013: R&D Engineer*
  * **Taiwan Semiconductor Manufacturing Company (TSMC, Hsinchu, Taiwan)**
    * Research and development on OPC, DPT, and process-aware optimization for manufacturing.

Skills
======
Programming Languages:
* Python, Perl, Tcl

ML / DL / RL Frameworks & Tools:
* PyTorch, TensorFlow, Keras, NumPy, Pandas, scikit-learn, XGBoost, LightGBM, Stable-Baselines, OpenAI Gym, MuJoCo, HuggingFace

Infra / Tools:
* Docker, Slurm, Kubernetes, AWS (S3/EC2/SageMaker)

VLSI / EDA Tools:
* Cadence Virtuoso / PVS, Synopsys Proteus / ProGen / IC Workbench, Mentor SVRF, Brion Tachyon
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Taipei animal shelter volunteer
