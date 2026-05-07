---
layout: page
title: LaMEM_pytools
description: A python library to process LaMEM code outputs
img:
importance: 4
category: Other
---

Here is given a python library designed to extract and process outputs from the [LaMEM](https://github.com/JuliaGeodynamics/LaMEM.jl) code {% cite kaus_forward_2016 %}.

You can find the LaMEM_pytools project at the following link: [https://github.com/YBoucharat/LaMEM_pytools](https://github.com/YBoucharat/LaMEM_pytools)

It allows to convert vtr, vts and vtu files (and also pvd files to extract simultaneously multiple timesteps) in xarray datasets under python.

Some computing tools are also provided, to extract different components of the topography. You can thus extract the isostatic topography, from lithosphere thinning or thickening, the dynamic topography, devided in 2 components, from the dynamic pressure and from the vertical deviatoric stress acting at the base of the lithosphere, and the rest topography, from shearing and other non normal forces acting inside the lithosphere.

It also provide an automatic trench detection, and a cut module to normalize your grid along a detected trench.

Inside the same repository, I provide two pvpython files (one for 2D setups and the other one for 3D setups) to automatically generate paraview figures.

