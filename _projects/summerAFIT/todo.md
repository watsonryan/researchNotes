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


- [ ] Robust Pose-graph Opt. 
  - [ ] Test Switchable Constrainst on Manhattan 3500
  - [ ] Automate Residual Collection from GTSAM 
  - [ ] Port GMM-DP from Python to C++
  - [ ] Test on other pose-graphs 

- [ ] IAE INS filtering 
  - [ ] Simulate INS data using PPP/INS Sim. 
  - [ ] Write Python Filter
