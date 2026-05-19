---
layout: page
title: REEF
description: Description of the REEF code
img: assets/img/Forwards.jpg
importance: 1
category: Geomorphology
related_publications: true
---

The REEF code is a kinematic profile evolution model, taking into account past sea-level, tectonic vertical movement and coral reef growth, erosional processes as input parameters.

REEF is available at the following link : [https://github.com/CRADOCS/REEF](https://github.com/CRADOCS/REEF)

<div style="display: flex; gap: 10px; align-items: flex-start;">
  <img src="/assets/img/Tryptich_intro.png" title="Controlling parameters" 
       style="height: 150px; width: auto;" class="rounded z-depth-1">
  <img src="/assets/img/REEF_processes.jpg" title="REEF processes" 
       style="height: 150px; width: auto;" class="rounded z-depth-1">
  <img src="/assets/img/Forwards.jpg" title="Forward model example" 
       style="height: 150px; width: auto;" class="rounded z-depth-1">
</div>
<div class="caption">
    The three controlling parameters are the past sea-level fluctuations, tectonics and geomorphic processes, which are coded in the code as described in the second figure. The figure on the right is an output example of the code, compared to a coral reef terrace sequence in Sumba, Indonesia.
</div>

The new version of the REEF code is written in python, but already need some fresh air ! Do not hesitate to contribute ! 

The first version has been published in Fortran by {% cite husson_reef_2018 %}, improved by {% cite pastier_genesis_2019 %}, and recoded in python and released in {% cite boucharat_probabilistic_2026 %}.
