---
layout: tasks
title : "ToDo for AFIT"
category: summerAFIT
---

## [ ] AFIT List

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


- [ ] Test E.M. Max-Mix Covariance Est. 
  - [ ] Breakdown point 
  - [ ] Confusion Matrix


- [ ] Write E.M. D.P. Max-Mix Optimization
  - [ ] Iterate between E.M and Max-Mix to reject outliers
  - [ ] Use Neyman–Pearson lemma to weight final Cov. Est. 

- [ ] IAE INS filtering 
  - [ ] Simulate INS data using PPP/INS Sim. 
  - [ ] Write Python Filter
