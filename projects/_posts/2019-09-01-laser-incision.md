---
layout: project
title: "Automated Laser Ablation of Soft Tissue"
handle: et
#image: /assets/images/projects/evolution-of-translation.svg
#category: project
#tags: [vocal folds, surgery, laser, continuum]
---
{% include JB/setup %}

Lasers are used in an increasingly number of surgical specialties to precisely cut and ablate tissue. Surgical lasers present a number of operational parameters -including beam intensity, number and frequency of pulses, etc. - that are not always intuitive to control. We are working on a technology that automatically regulates these parameters based on high-level inputs from the surgeon - e.g. "I wish to make an incision 1 mm deep". In prior studies, we demonstrated that automating laser incisions enables sub-millimeter accuracy, something that only a small number of exceptional surgeons can currently achieve using microscopes and hand-aimed laser systems.

Our approach uses a controller based on a model that maps the desired ablation depth to the required laser parameters (power, pulse duration, exposure time). Building such a model would normally involve solving the differential equations that govern laser-tissue interactions, but these are generally difficult to solve in closed form and even numerical solutions require many assumptions that cannot be made with high confidence in a realistic surgical setting. In contrast, our approach involves learning the mapping through repeated observations - just like humans do. Supervised machine learning enables the creation of models that capture and reproduce the surgeon’s mental estimation of the laser incision depth, i.e. models capable of mapping the laser inputs to the resulting depth.


<iframe width="560" height="315" src="https://www.youtube.com/embed/vDfdoLf9J3s" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
