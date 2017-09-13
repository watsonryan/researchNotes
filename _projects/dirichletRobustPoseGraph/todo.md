---
layout: tasks
title : "ToDo for AFIT"
category: dirichletRobustPoseGraph
---

## [ ] Dirichlet Pose Graph Optimization 

- [x] Generate GNSS Data
   - [x] dual receivers 
     - [x] one high quality receiver with faults 
     - [x] one low quality with no faults
- [x] Test generic M-Estimation techniques
    - [x] ref::  [hybrid inference paper](http://www.robots.ox.ac.uk/~avsegal/resources/papers/segal2014hybrid.pdf)
- [x] Test new graph based methods 
    - [ x] Test switchable constraints
        - [x ] try between switchable constraints ( time const. ) 
    - [ x] Test DCS 
    - [ x] Test Max Mixtures 
    - [ x] Test Realizing, Reversing, Recovering
- [x] read [Condensed Measurements](http://kaini.org/assets/Grisetti12iros.pdf) paper
    - [x ] possible link to [ smart factor ](http://www.cc.gatech.edu/~dellaert/pub/Carlone14icra.pdf)


- [x] Robust Pose-graph Opt. 
  - [x] Test Switchable Constrainst on Manhattan 3500
  - [x] Automate Residual Collection from GTSAM 
  - [x] Port GMM-DP from Python to C++
  - [x] Test on other pose-graphs 


- [x] Test E.M. Max-Mix Covariance Est. 
  - [x] Breakdown point 
  - [x] Confusion Matrix


- [x] Write E.M. D.P. Max-Mix Optimization
  - [x] Iterate between E.M and Max-Mix to reject outliers
  - [x] Use Neyman–Pearson lemma to weight final Cov. Est. 

- [ ] Test D.P Max-Mix on poor initial covariance graph
    - [] vary noise on pose-graph constraints
    - [] compare S.C., (unmodified) MM, and D.P. M.M

- [ ] IAE INS filtering 
  - [] Simulate INS data using PPP/INS Sim. 
  - [] Write Python Filter
