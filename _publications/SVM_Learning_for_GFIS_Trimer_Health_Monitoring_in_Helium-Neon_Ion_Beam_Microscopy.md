---
title: "SVM Learning for GFIS Trimer Health Monitoring in Helium-Neon Ion Beam Microscopy"
collection: publications
permalink: /_publication/SVM_Learning_for_GFIS_Trimer_Health_Monitoring_in_Helium-Neon_Ion_Beam_Microscopy
date: 2019-10-22
venue: 'Advanced Process Control Conference (APC)'
paperurl: 'https://vlsicad.ucsd.edu/Publications/Conferences/372/c372.pdf'
citation: 'Kahng, A. B., Liu, H. Y., Park, C., Pichumani, R., & Saul, L. SVM Learning for GFIS Trimer Health Monitoring in Helium-Neon Ion Beam Microscopy., Advanced Process Control Conference, 2019'
---

![Identifying an unhealthy trimer](/images/Trimer_SVM.png)

Helium-Neon ion beam microscopy (HIM) has shown significant promise in the areas of nanoscale imaging, editing, 
and patterning of semiconductor structures. The unique capabilities of this technology are enabling new applications 
in semiconductor process control by exploiting the ability to characterize materials in the sub-5 nanometer spatial scale with high speed.  

These instruments utilize a gas field ion source (GFIS) trimer with an atomically sharp metal tip to generate a stream of 
charged particles that are used for imaging and milling. As these applications move into high-throughput fabrication and measurement domains, 
it becomes increasingly important to optimize the stability and reliability of the imaging column to achieve the most useful results.  

One critical factor impacting repeatable tool operation is the ability to maintain the precise atomic structure of atoms comprising 
the source GFIS trimer. In this work, we propose the first machinelearning-based support vector machine model to monitor whether 
the current GFIS trimer is healthy or not for imaging.  

With an original dataset of 726 images our model achieves precisions of 97% 
for the “Healthy” class and 98% for the “Unhealthy” class with leave-one-out cross-validation. Even with a large amount of augmented 
data (21X of the original data) as input (total of 15246 images), we still reach precisions of 97% for the “Healthy” class and 95% 
for the “Unhealthy” class. The significance of this work is the ability to support in-line predictive maintenance, optimal performance, 
and equipment productivity in semiconductor fab environments.