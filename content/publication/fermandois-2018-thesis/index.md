---
title: Development and implementation of a multi-axial real-time hybrid simulation
  framework
date: '2018-01-01'
publishDate: '2021-03-02T11:05:52.291939Z'
authors:
- Gaston A. Fermandois
publication_types:
- '7'
abstract: Real-time hybrid simulation is an efficient and cost-effective experimental
  testing technique for performance evaluation of structural systems subjected to
  earthquake loading with rate-dependent behavior. To assess the response of structural
  components with multi-axial loading, a loading assembly with multiple parallel actuators
  connected to a rigid moving platform is required to impose realistic boundary conditions
  on physical components. This loading assembly is expected to exhibit significant
  dynamic actuator coupling and suffer from systematic errors and potential instabilities.
  One approach to reduce experimental errors considers a multi-input, multi-output
  (MIMO) modeling approach to design controllers that could compensate for these undesired
  effects. In this dissertation, a framework for three-dimensional, multi-axial real-time
  hybrid simulation is presented. The methodology consists in designing a real-time
  system platform to perform dynamic test experiments by controlling the interface
  boundary conditions on the physical specimen in Cartesian (global) coordinates.
  First, a kinematic transformation is derived to impose the six-degree-of-freedom
  motion to the loading platform in three-dimensional Cartesian space. Then, a linearized
  model of the multi-actuator loading assembly is obtained through nonparametric frequency
  domain system identification techniques. Subsequently, a feedforward-feedback compensator
  is developed for reference tracking of the multivariate transient signals, which
  should be sufficiently robust to rule out any disturbances and measurement noises
  in the experimental closed-loop system. Finally, the numerical substructure, compensators,
  and kinematic transformations are implemented over an embedded system with a micro-controller
  unit and digital signal processing capabilities for real-time applications. The
  proposed framework is validated using a small-scale version of the Load and Boundary
  Condition Box (LBCB) from Newmark Civil Engineering Laboratory at University of
  Illinois, Urbana-Champaign. A one-story, two-bay, moment frame was considered as
  the reference structure, where the experimental substructure was chosen as a steel
  column with fixed ends. The hybrid system was subjected to earthquake ground motions
  chosen according to its importance and destructive characteristics. Comparisons
  of different compensation strategies are made, and excellent performance is achieved
  for all situations that incorporates the multivariate controller.
featured: false
publication: ''
url_pdf: http://hdl.handle.net/2142/101133
---

