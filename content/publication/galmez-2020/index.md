---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Online Stability Analysis for Real-Time Hybrid Simulation Testing
subtitle: ''
summary: ''
authors:
- Cristóbal Gálmez
- Gastón Fermandois
tags:
- 'delay'
- 'energy methods'
- 'negative damping'
- 'real-time hybrid simulation'
- 'stability analysis'
categories: []
date: '2020-08-01'
lastmod: 2020-09-13T17:13:03-03:00
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
publishDate: '2020-09-13T20:13:03.005019Z'
publication_types:
- 2
abstract: Real-time hybrid simulation (RTHS) is an experimental technique where a critical element of a structural system is tested in the laboratory while the rest is represented through numerical simulations. A challenging aspect of this technique is the correct application of boundary conditions on the experimental substructure using actuators and sensors. The inherent dynamics of an actuator and its interaction with the physical specimen causes a time delay between commanded and measured displacements. It has been shown that delay in RTHS affects the accuracy of an experiment and even can cause instability. Therefore, to avoid stability problems, a proper partitioning choice and an appropriate compensation method for actuator dynamics should be considered. However, there will always be uncertainty in the experimental structure's behavior, so it is essential to check the system's stability during the test execution. In this paper, a stability analysis using energy methods is performed to develop an online stability indicator for the RTHS test. This indicator's goal is to detect stability problems before it can cause excessive displacements in the system, thus avoiding damage in the physical specimen or the laboratory equipment. The effectiveness of the proposed online stability indicator is demonstrated through numerical simulations taking into account the virtual RTHS benchmark problem with different compensation strategies. The proposed indicator is an excellent tool to monitor the RTHS test, improving the reliability of the experimental test while maintaining the safety of the laboratory resources.
publication: '*Frontiers in Built Environment*'
url_pdf: https://www.frontiersin.org/article/10.3389/fbuil.2020.00134/full
doi: 10.3389/fbuil.2020.00134
---
