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
* Ph.D in Computer Engineering, University of California San Diego, 2023 (expected)
* M.S. in Optoelectronics, National Taiwan University, 2008
* B.S. in Physics, National Central University, 2005

Work experience
======
* *Sep. 2018 ~ Now: Graduate Student Researcher*
  * **University of California - San Diego (La Jolla, CA, USA)**
    * Deep Reinforcement Learning research:
      ** Online/Offline RL policy regularization
      ** Open-source dataset for offline-RL
      ** Incorporating existing policy with RL
      ** Offline-to-Online RL
    * Building HVAC control with RL


* *Summer 2020: Machine Learning Intern-Software Engineer*
  * **Cadence Design Systems Inc. (Milpitas, CA, USA)**
    * Create functions for automatically generating partitions to accelerate design space exploration:
    * Include most of the critical paths distribution in entire design
    * Partitions with reduced design area and instance numbers by a factor around 1/3 to 1/4 
    * Prototyping with both Machine Learning clustering (DBSCAN) and heat map grid-based algorithms

* *2013 ~ 2018: Principal Application Engineer*
  * **Cadence Design Systems Inc.**
    * Develop customized GUIs/scripts using Cadence SKILL
    * Mask data preparation for foundry N14/N28 reticle frames
    * Host customer training and workshops
    * Co-work with R&D for functionality improvement, bug-fix and performance enhancement
  
* *2009 ~ 2013: OPC R&D Engineer*
  * **Taiwan Semiconductor Manufacturing Company (TSMC)**
    * N20 interconnection layers OPC model build-up, OPC and DPT recipe optimization. (ProGen, Proteus)
    * Path-finding and optimization of double patterning issues: Odd-loop, VCMS, pattern loading, etc.
    * Aerial/resist image simulations for design rule & process robustness evaluation. (Brion Tachyon, S-Litho, ICWB)
    * Resolution enhancement researches: Forbidden pitch, combined source of annular and quasar, SMO, etc.( S-Litho)
    * Flow automation, such as pattern density calculator, DPT-to-OPC flow connector, etc. (Perl)
    * VCMS (Via-Correlated Metal Separation): BEOL dual damascene LELE cross-layer  DPT overlay reduction scheme
    * Rule deck creation and optimization: LOP/MRC/XOR/CRC, etc. (Calibre DRC)
    * Test mask creations: PMK/OMK/VMK/DMK, etc. (Tcl, Laker)
    * Rule-based OPC for interconnection layers restricted rule

Skills
======
* Progamming Language:
  * Python / Tcl/ Perl/ SKILL (Cadence)
* Software:
  ** Machine Learning/Data Science: pytorch, tensorflow, numpy, matplotlib
  ** VLSI/OPC: Cadence Virtuoso/PVS, Synopsys Proteus/ProGen/IC Workbench/DFM, Mentor SVRF, Brion Tachyon, etc.
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Taipei animal shelter volunteer
