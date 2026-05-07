---
layout: page
title: RoSETTA
description: "RoSETTA code: Reconstruction Of Sea-level, Ecosystems and Tectonics from Terrace Analysis"
img: assets/img/RoSETTA_algo.jpg
importance: 2
category: Geomorphology
giscus_comments: true
---

This code is a combination of a coral reef construction model {% cite boucharat_probabilistic_2025 husson_reef_2018 pastier_genesis_2019 %} and a bayesian inversion model {% cite hedjazian_optimal_2018 %}. The resulting ROSETTA model runs a given number of forward REEF models, in order to diminish the misfit between the modelled and observed 1-D topographic profile, using a Monte-Carlo Markov Chain (MCMC) sampling. Based on a Bayesian framework, the solution of our model is a posterior probability distribution describing the probability of the model parameters (here the past sea-level variations and the REEF parameters), given the observed data (here the topo-bathymetry of a marine terrace sequence).

RoSETTA is available at the following link: [https://github.com/CRADOCS/RoSETTA](https://github.com/CRADOCS/RoSETTA)

