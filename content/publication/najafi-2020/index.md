---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Decoupled model-based real-time hybrid simulation with multi-axial load and
  boundary condition boxes
subtitle: ''
summary: ''
authors:
- Amirali Najafi
- Gaston A. Fermandois
- Billie F. Spencer
tags:
- '"Dynamic coupling"'
- '"Kinematic transformation"'
- '"Model-based compensation"'
- '"Multiple actuators"'
- '"Real-time hybrid simulation"'
categories: []
date: '2020-09-01'
lastmod: 2020-09-13T17:13:02-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-03-02T11:05:51.764493Z'
publication_types:
- '2'
abstract: Real-time hybrid simulation (RTHS) is a cost and space efficient alternative
  to shake table testing for seismic assessment of structural systems. In this method,
  complete structural systems are partitioned into numerical and physical components
  and tested at real earthquake velocities. Well-understood components of the structure
  are modeled in finite-element numerical models. Meanwhile, the physical substructure,
  which often contains the highly nonlinear and numerically burdensome components
  is fabricated and tested in a laboratory facility. Testing at real earthquake velocities
  is useful to obtain nonlinear rate-dependent material behaviors. Realistic reproduction
  of seismic conditions for structural assessment has required researchers to develop
  multi-axial RTHS capabilities. In such developments, multiple actuators are arranged
  at the boundary condition with the physical specimen to impose realistic displacements
  and rotations. But, varying degrees of dynamic coupling exist between the actuators
  in multi-axial boundary conditions. Controllers and kinematic transformations are
  developed for the tracking action of the actuators to compensate for the amplitude
  and phase discrepancies between target and measured displacement signals, otherwise
  stability issues are likely to result. In this paper, a multi-axial framework is
  introduced for RTHS testing, using a Load and Boundary Condition Box (LBCB) at the
  University of Illinois at Urbana-Champaign. The previously developed multi-axial
  RTHS framework for the LBCBs compensates for actuator dynamics in Cartesian coordinates;
  this approach lacked stability robustness when testing stiff specimens. The distinguishing
  feature of the proposed framework is that tracking compensation is executed in the
  actuator coordinates. The differences between the previous and proposed multi-axial
  RTHS frameworks are explored in detail herein. This paper presents the components
  of the framework and the describes a six-degree-of-freedom moment frame RTHS experiment.
  Finally, experimental results are discussed and directions for future research efforts
  are considered.
publication: '*Engineering Structures*'
url_pdf: https://linkinghub.elsevier.com/retrieve/pii/S0141029619344219
doi: 10.1016/j.engstruct.2020.110868
---
